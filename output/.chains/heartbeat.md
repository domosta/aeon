⚠️ Heartbeat: fleet not dispatching

## 🔴 Heartbeat - DEGRADED: scheduled workflows stopped

**No scheduled run has fired since 2026-11-16 20:41 UTC (~60h ago).** All three enabled daily skills are overdue; this heartbeat run was a manual dispatch.

**🔴 P0 - agent not being dispatched**
- `heartbeat` self-check: last success 2026-11-16 19:29 UTC, **>36h stale** → heartbeat itself may be unreliable.
- Evidence: GitHub Actions shows the last `scheduler: cron` run at 2026-11-16 18:24 and the last `poll` at 2026-11-16 20:41; nothing since until this manual run. The cron trigger itself appears to have stopped firing.

**🟡 P3 - overdue scheduled skills (>2× their daily interval)**
| Skill | Schedule | Last success | Age |
|-------|----------|--------------|-----|
| flovia | 05:30 daily | 2026-11-16 07:56 | ~73h |
| revenue-alert | 05:30 daily | 2026-11-16 07:58 | ~73h |
| heartbeat | 08:00 daily | 2026-11-16 19:29 | ~61h |

**🟢 P1 / P2 - clear**
- No open PRs; no `urgent`-labelled GitHub issues; nothing flagged in `memory/MEMORY.md`.
- Two unlabelled machine-managed health threads remain open (GitHub #1 `investigation-report`, #2 `heartbeat`) - informational only.

**Action:** check repo **Settings → Actions → General** (scheduled workflows not disabled) and the Actions tab for a repo-level disable/outage event around 2026-11-16 20:41 UTC.

`STATUS_PAGE=DEGRADED` - `docs/status.md` regenerated.