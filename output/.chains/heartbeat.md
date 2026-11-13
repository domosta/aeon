🚨 Heartbeat: fleet DEGRADED - OpenRouter 402

🔴 **Fleet degraded - model backend out of credits**

OpenRouter returns HTTP **402 "Insufficient credits"** on every run of the default model. Two skills are failing with that identical error - a shared dependency failure, not per-skill bugs:

- **heartbeat** - 2 consecutive failures (last 2026-11-13 02:35 UTC)
- **investigation-report** - 2 consecutive failures (last 2026-11-12 15:45 UTC)

**Action:** top up the OpenRouter account or point the default model at a funded provider. Until then, every default-model skill run fails.

🟡 **revenue-alert - enabled but never dispatched**
`revenue-alert` is enabled on a daily 08:30 UTC schedule but has no entry in `memory/cron-state.json`, so the scheduler has never run it. Check its workflow wiring.

Status page: 🔴 DEGRADED (`docs/status.md`)