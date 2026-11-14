⚠️ Heartbeat - fleet recovered; status page still red

🟢 RECOVERED - model backend: `heartbeat`, `flovia`, `revenue-alert` and `defi-overview` all succeeded since 2026-11-13. The OpenRouter HTTP 402 "Insufficient credits" outage that reddened the page yesterday is over.

🔴 PAGE still shows DEGRADED - `docs/status.md` reads 🔴 only because the now-disabled `investigation-report` still carries a non-recovered failure (2 consecutive failures, last 2026-11-12 15:45 UTC). A disabled skill can't self-recover, so re-enable + re-run it once to clear the entry, or the page keeps reading red.

🟡 WATCH - `onchain-monitor` (enabled, daily 12:00 UTC) has no entry in `memory/cron-state.json`, i.e. never dispatched. If it was just enabled it's simply warming up; otherwise the scheduler may not be wired to it.