# DukaanOS

**Your Shop. Your Stock. Your Growth.**

A simple, free inventory, billing and business-insights app for small Indian shopkeepers. Built for **PromptWars × Kick To Tech 2026** (Entrepreneurship & Local Business track).

**Live demo:** https://claude.ai/artifact/WRn24LQNyERfhjyqW2K8my

---

## Problem

Millions of kirana and neighbourhood shops still track stock in notebooks or in their heads. This causes three everyday problems:

- **Stock-outs:** popular items run out before the shopkeeper notices.
- **Unclear profit:** daily takings are known, but profit is not.
- **Costly tools:** most inventory software is priced, complex, or needs training and internet setup.

## Target users

- Owners of kirana, general, stationery, and small retail stores
- Shop staff who bill customers at the counter
- Micro-entrepreneurs starting a small shop who need a free tool

## Solution

DukaanOS puts products, billing, stock alerts and simple analytics in one clean dashboard. It runs in any modern browser, needs no account, no backend and no paid service, and keeps data on the device.

## Features

| Module | What it does |
|---|---|
| **Dashboard** | Live metrics: active products, total stock units, today's revenue, estimated gross profit, low-stock count. Revenue and profit are shown separately. Includes a 7-day sales chart, best sellers, recent sales and quick actions. |
| **Inventory** | Add, edit, delete (with confirmation) and view products. Search, filter by category, sort by name, price or stock. Full validation (empty names, negative prices, non-integer stock, duplicate IDs). Status badges: In Stock, Low Stock, Out of Stock. |
| **Sales & Billing** | Build a multi-item bill, see line totals and subtotal, confirm the sale. Prevents selling more than available stock, deducts stock automatically, records date and time, and shows a printable receipt. Amounts use Indian Rupee formatting. |
| **Stock Alerts** | Lists products at or below their threshold, with remaining quantity, threshold and a suggested restock quantity. Filters for low-stock and out-of-stock. Updates after every sale or edit. |
| **Business Insights** | Revenue and gross profit over time, sales by product, best sellers and inventory status, all calculated from recorded transactions. Seeded demo sales are clearly labelled as sample data. |
| **Smart Insights** | Transparent, rule-based suggestions (restock, frequent sellers, unsold products, profit by product, low-margin warnings). No AI model is connected, and the page says so. |
| **Data & UX** | Data persists in localStorage. Invalid stored data is handled safely. Reset-demo-data option with confirmation. Editable shop profile, notification badge, responsive layout with mobile menu, keyboard-friendly forms, and automatic dark mode. |

> DukaanOS is a sales-recording and billing prototype. It does not process payments.

## Technology

- HTML, CSS and vanilla JavaScript in a single file (`index.html`)
- Browser `localStorage` for persistence
- Inline SVG logo and CSS-based charts
- No frameworks, no build step, no external libraries, no API keys
- Built with AI-assisted development (vibe coding) during the hackathon

## How to run

**Option 1: open the file**
1. Download `index.html`.
2. Double-click it to open it in Chrome, Edge, Firefox or Safari.

**Option 2: local server**
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

**Option 3: GitHub Pages**
Push `index.html` to a repository, then enable Settings → Pages → Deploy from branch.

The app works offline once the file is on your computer.

## Suggested demo flow

1. Open the **Dashboard** and note today's revenue and estimated profit.
2. **Add a product** and see it in **Inventory**.
3. **Record a sale** of that product.
4. Watch **stock deduct** and the dashboard update.
5. Sell enough to cross the threshold and open **Stock Alerts**.
6. Open **Business Insights** and **Smart Insights**.
7. **Refresh the browser** to show data persistence.

## Testing performed

Manual testing by the developer of the main features: product add, edit and delete, sales and stock deduction, dashboard updates, and navigation. No automated test suite is included.

## Known limitations

- Data lives in one browser on one device. There is no cloud sync, multi-device or multi-user support.
- Clearing browser data erases shop data. There is no export or backup feature yet.
- No GST or tax invoicing, barcode scanning, supplier management, or returns.
- Insights are simple rules, not machine learning.
- Seeded sales are sample data for demonstration only.
- Not formally tested on every browser or device.

## Roadmap

CSV export and backup, GST-ready invoices, barcode scanning, Hindi and regional-language UI, optional cloud sync, and WhatsApp restock messages to suppliers.

## License

Created for hackathon submission. Add a license of your choice before publishing publicly.
