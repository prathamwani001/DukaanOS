# DukaanOS: Submission Pack

## Part 1: Project Summary

**Project name:** DukaanOS

**Tagline:** Your Shop. Your Stock. Your Growth.

**Problem statement:**
Small Indian shopkeepers often track stock on paper or from memory. They run out of popular items, cannot see their real profit, and find existing software too expensive or complicated.

**Proposed solution:**
DukaanOS is a free, browser-based dashboard for inventory, billing, stock alerts and business insights. It needs no account, no internet backend and no paid service. A shopkeeper can add products, bill customers, and see stock and profit update instantly.

**Key features:**
- Live dashboard: revenue and estimated gross profit shown separately, plus stock and low-stock counts
- Inventory management with validation, search, filter, sort and delete confirmation
- Multi-item billing with stock-limit checks, automatic stock deduction and printable receipts
- Automatic low-stock alerts with suggested restock quantities
- Analytics from real transaction records
- Transparent rule-based Smart Insights
- Data saved on the device; reset-demo option with confirmation; mobile-friendly

**Innovation and uniqueness:**
- Built for the real constraints of a neighbourhood shop: free, simple, works offline, nothing to install.
- Keeps revenue and profit clearly separate, since shopkeepers often confuse them.
- Suggests restock quantities, not just warnings.
- Honest insights: every suggestion comes from a visible rule, with no fake "AI" claims.
- Sample data is labelled, and analytics never invent performance numbers.

**Technology used:**
HTML, CSS and vanilla JavaScript in a single file, browser localStorage, inline SVG and CSS charts. No backend, no API keys. Developed with AI-assisted coding (vibe coding).

**Testing performed:**
Manual testing by the developer of product add, edit and delete, sales and stock deduction, dashboard updates and navigation. No automated tests.

**Current limitations:**
Single-device storage with no cloud sync or multi-user support; no backup or export yet; no GST invoicing or barcode scanning; insights are simple rules, not ML; not formally tested across all browsers.

---

## Part 2: 3-Minute Presentation Script

**Before you start:** open the app on the Dashboard. Do one practice run first.

**0:00 – 0:30 | The problem**
"Namaste. India has millions of small shops, and many still run on a notebook. The shopkeeper knows what he earned today, but not what he *profited*, and he often finds out an item is finished only when a customer asks for it. Existing software costs money and needs training. That's the gap."

**0:30 – 0:45 | The solution**
"This is DukaanOS: Your Shop, Your Stock, Your Growth. A free dashboard that runs in any browser, with no account and no backend."

**0:45 – 2:30 | Live demo** *(say each line while doing the action)*
1. "This is the dashboard. Revenue and estimated profit are shown separately, because they are different things." *(point at both cards)*
2. "Let me add a new product." *(Add product, fill the form, save. Show validation by leaving the name empty first, if time allows.)*
3. "It appears in Inventory, with a stock status badge."
4. "Now a customer buys it." *(Sales: pick the product, quantity, add to bill, confirm.)* "The receipt is ready to print."
5. "Back on the dashboard, stock is deducted, revenue is up, and so is estimated profit."
6. "If stock falls to the threshold, we get an alert with a suggested restock quantity." *(Open Stock Alerts.)*
7. "Business Insights show revenue, profit and best sellers from real transactions. Smart Insights gives plain-language suggestions, and every one comes from a visible rule."
8. "And if I refresh the browser…" *(refresh)* "…all the data is still here."

**2:30 – 3:00 | Close**
"DukaanOS is built for a neighbourhood shop: free, simple, and honest about what it knows. Next we would add CSV backup, GST invoices, barcode scanning and Hindi support. Thank you."

**Tips:** speak slowly; keep a second tab ready with the app loaded in case of a connection problem; if something fails, say what should happen and move on.

---

## Part 3: Likely Judge Questions and Easy Answers

**1. Who is this for?**
Small shop owners such as kirana and general stores who want a free, simple way to manage stock and see profit.

**2. How is it different from existing billing apps?**
It is free, needs no signup or training, works offline, and focuses on the shopkeeper's real questions: what is running out, and what am I really earning?

**3. Is there AI in it?**
The suggestions are rule-based, and the app says so. We used AI to *build* the project quickly. A natural next step is adding a real AI layer, for example demand forecasting, once there is enough sales history.

**4. Where is the data stored? Is it safe?**
On the user's own device in browser storage. Nothing is sent to a server, so there is no data leak risk from us. The trade-off is no sync or backup yet, which is on the roadmap.

**5. What happens if the browser data is cleared?**
The shop data is lost. That is why CSV export and backup are our first roadmap item.

**6. How do you calculate profit?**
Estimated gross profit = (selling price − cost price) × quantity sold. It does not include rent, salaries or tax, which is why we call it "estimated gross profit".

**7. Does it handle payments?**
No. It records sales and generates receipts. It is a billing prototype, not a payment gateway.

**8. How did you prevent errors, like selling more than in stock?**
The sale is blocked when the quantity exceeds available stock, and product forms validate names, prices, stock and duplicate IDs.

**9. What did you test?**
I manually tested the main flows: adding, editing and deleting products, sales and stock deduction, dashboard updates and navigation. There are no automated tests yet.

**10. Can it scale to multiple shops or staff?**
Not in this version. It would need a backend and user accounts. The data model (products, sales, shop settings) is already separated, so it can move to a database.

**11. How would you make money?**
Keep the core free. Offer paid add-ons later: cloud backup, multi-shop dashboards, GST filing support and supplier ordering.

**12. What are the next steps?**
CSV backup, GST-ready invoices, barcode scanning, Hindi and regional languages, optional cloud sync, and WhatsApp restock messages to suppliers.

**13. What was the hardest part?**
Keeping the app simple enough for a non-technical shopkeeper while still making every number come from real data.
