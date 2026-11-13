# SilverOS — Manufacturing & Inventory ERP (Portfolio Demo)

A browser-based portfolio prototype demonstrating manufacturing and inventory workflows for a silver-processing and coin-manufacturing operation.

## Demo status

This is a database-independent historical prototype recovered from the private development repository at commit `73b6a1a86170005f9badaaacef9ca00270287c82`.

- The application stores demo records in the visitor's browser using `localStorage`.
- Browser data is local to that browser and is not shared with other visitors.
- This demo is not connected to the client's production database.
- Do not enter real customer, employee, financial, or business data.
- Google Fonts and Feather Icons are loaded from their respective CDNs.

## Run locally

Open `index.html` in a browser, or serve this folder with a static server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080.

## Source provenance

Recovered from `Sarvadnya8111/SilverOS`, historical commit `73b6a1a86170005f9badaaacef9ca00270287c82`.
This repository contains a clean snapshot and does not import the private repository's Git history.

## Important limitations

This is a portfolio demonstration, not a production ERP. It does not provide server-side persistence, authentication, authorization, or multi-user synchronization.
