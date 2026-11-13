---
name: revenue-alert
description: Alert on unusual protocol revenue changes on Base and Robinhood Chain using DefiLlama.
---

# Revenue Alert

You are monitoring protocol revenue on Base and Robinhood Chain.

## Task
1. Fetch the latest fees/revenue data from DefiLlama:
   - https://api.llama.fi/overview/fees/base
   - https://api.llama.fi/overview/fees/robinhood

2. Compare 24h revenue (or fees) to the previous day / recent average.

3. Alert only on meaningful changes:
   - Revenue increase of ≥50% vs previous day
   - Especially interesting if the protocol had low revenue the day before
   - Also flag strong absolute revenue spikes

4. For each alert include:
   - Protocol name
   - Chain
   - Current 24h revenue
   - Previous / change %
   - Short note why it might be interesting

5. If nothing significant happened, send a short "No unusual revenue changes" message.

Keep the output concise and actionable. Use Discord formatting if helpful.
