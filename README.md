# Digitalcoo CRM — Demo

Interactive prototype of the operations platform for **Digitalcoo Technologies LLC** (e& Authorised Channel Partner).

**Live demo:** open `index.html` in any browser, or visit the GitHub Pages link.

## What this is
A clickable front-end prototype to review the workflow before the real system is built. It covers:

- **DSR — Agent**: agents build their calling list, log calls, update status (with permanent DSR numbers, duplicate-contact alerts, and full change history).
- **Sales Pipeline**: opportunities by stage, weighted forecast, escalation to Sales Head.
- **Back Office / Orders**: order processing with e& (PID, activation, status lifecycle).
- **MIS & Targets**: target vs submission vs activation, team-leader roll-ups, commission.
- **HR / Payroll / Accounting**: employee master, WPS payroll + gratuity, VAT 5% / Corporate Tax 9% / IFRS P&L view.
- **AI Reports**: auto daily / weekly / monthly summaries.
- **Admin**: role-based access control (editable) and extensibility to other King Group segments.

## How to review
Sign in as any role (Agent, Team Leader, Teams Head, Sales Head, Back Office, Accountant, HR, Admin) to see that role's permissions in action.

## Important notes (prototype)
- **Data is local to each browser** (localStorage). Your changes are not shared with others and are not stored centrally. Use **Reset demo data** to restore the sample.
- **No real login/security** — the role buttons are a demo switch only.
- Accounting/tax figures use simplified logic for illustration.

_Built as a working prototype. The production build (database, real multi-user login, audit trail, EmaraTax/WPS exports, automated reports) follows platform selection._
