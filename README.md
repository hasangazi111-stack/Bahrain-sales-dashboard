# Bahrain Sales Channel Intelligence

Interactive browser dashboard with colorful executive KPIs, sales/agent/customer/revenue views, filters, map, CSV export and a local dashboard analyst chat assistant.

## Run locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Publish with GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.

## Data and assistant

This standalone prototype creates deterministic synthetic demonstration records in the browser; it does not connect to a real sales system. The chat assistant calculates answers in the browser using the active filters. It is not a cloud LLM and does not transmit customer data. A true generative AI assistant needs a server-side API integration; keep provider credentials on that server, never in this public HTML or browser JavaScript.
