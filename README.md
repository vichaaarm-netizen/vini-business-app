# VINI Business Solutions – iPhone app starter

## Included
- Service sales and payment tracking
- Expense recording and categories
- Clients and outstanding balances
- Ongoing works with status and progress
- Date-range reports, service/expense breakdowns
- CSV export, JSON backup/restore
- Printable invoices (use iPhone Print > Save as PDF)
- MVR currency display
- Installable PWA layout for iPhone

## Important first-version limitation
This version stores records locally in the browser on the device. It does not yet have Firebase/cloud sync, user accounts, automatic multi-device backup, or server-side security. Do not clear Safari website data without exporting a backup first. The app is owner-only by design.

## Make it installable on iPhone
A PWA must be hosted on an HTTPS website:
1. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to a static HTTPS host (GitHub Pages is one free option).
2. Open the hosted website in Safari on the iPhone.
3. Tap Share > Add to Home Screen > Add.
4. Open the VINI icon from the Home Screen.

## Recommended next development step
Connect Firebase (Firestore + Authentication) and add a secure owner login and cloud backup before using it for important business records. Also add your official business contact details and invoice numbering/tax settings before issuing invoices to customers.
