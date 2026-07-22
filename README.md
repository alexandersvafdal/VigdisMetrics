# vigdis-metrics

The Vigdís internal metrics dashboard **shell** — it contains no data.
Open it and load `vigdis-data.json` (from iCloud Drive → Vigdis, produced by
`app-store-connect-mcp/build_dashboard.py`) to see the dashboard.

To update after dashboard code changes: rebuild (`python3 build_dashboard.py
--bundle` next door), which refreshes `index.html` here, then commit + push —
GitHub Pages redeploys automatically.
