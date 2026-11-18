# Fund & Loan Management System — clickable prototype

Single-file prototype (`index.html`) with sample data. No build step and no server: open `index.html` in a browser, or host it as a static page.

## What it covers
- **Fund:** Pool & Allocation (investor funds split across companies, each with its own COF %), Fund Dashboard (company inflow/outflow, cash on hand, P&L after COF and expenses, pool check, principal maturities).
- **Companies:** per company — Overview, Loan management (CapBoost cases, Capbridge-i invoices, customers) and Expenses.
- **Clients:** customer and case pages (loan details, remarks, repayment schedule with late (OD) charges and Extra, settlement, OCR payment pop-up, timeline, commission), new customer from pasted text or application form, Specific Account.
- **Records:** Commission setup (formula per team, New / Existing case), Ledger, Settings (company setup with CapBoost / Capbridge-i frameworks, roles).

## Notes
- All data is sample data, saved in the browser's localStorage (key `flms-proto-v1`). Use **Reset sample data** in the sidebar to start again.
- OCR (payment slips, invoices, application forms, receipts) is simulated.
- Roles are a demo switcher at the bottom of the sidebar (no login yet).
- Planned build: Next.js + Postgres on Google Cloud (Cloud Run + Cloud SQL).
