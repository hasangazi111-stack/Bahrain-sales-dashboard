# Bahrain Sales Channel Intelligence

A standalone browser-based interactive dashboard for the Bahrain telecom sales channel.

## Run locally

Open `index.html` directly in a browser, or serve the repository:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

1. Open the repository **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main** and `/ (root)`.
5. Save.

The dashboard generates 28,000 deterministic synthetic activation records in the browser. No backend or database is required.

## Features

- Executive, sales, agent, customer, map, revenue, partner, target and record views
- Date, agent, activation area, partner and nationality filters
- Interactive area and partner analysis
- Leaflet/OpenStreetMap activation map
- Agent leaderboard and target tracking
- Customer record search
- CSV export

All customer names, mobile numbers and CPR references are fictional. The prototype target is 40 activations per agent per selected period.
