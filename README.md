# Bahrain Sales Channel Intelligence

Interactive browser dashboard with synthetic activations, sales/agent/customer views, map, filters, CSV export and a local dashboard analyst chat assistant.

## Product Type scenario view

Open [`product-type.html`](product-type.html) for the separate Product Type analysis page. It illustrates the requested 67% / 23% / 10% allocation for Products A/B/C, priced at BD 10 / BD 12 / BD 15 per month. Product Type is not included in the supplied activation schema, so this view is explicitly a synthetic planning scenario rather than actual product-level sales. It does not modify or disrupt the main dashboard.

## Run locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000` for the main dashboard or `http://localhost:8000/product-type.html` for Product Type Analysis.

## Publish with GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. Pages publishes both HTML files.

## Assistant and data

The main dashboard assistant calculates answers in the browser from the current filters. Demo records and the product mix are synthetic; no customer data is sent to an AI service.
