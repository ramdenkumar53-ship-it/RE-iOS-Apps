# Vivek AI Business — MVP 1.0

A lightweight Hindi/English Progressive Web App (PWA) starter for small-business planning.

## Features
- Budget- and interest-based business idea suggestions (rule/template based; no AI API yet)
- Seven-day starter checklist
- WhatsApp promotional copy generator and share link
- Sales/expense ledger stored in browser localStorage
- CSV export
- Installable PWA shell and basic offline cache

## Run locally
Open `index.html` in a browser. For full PWA install/offline support, serve over HTTPS (GitHub Pages works).

## Deploy with GitHub Pages
1. Create a public repository named `vivek-ai-business`.
2. Upload all files from this folder to the repository root.
3. Open Settings → Pages.
4. Under Build and deployment, select Deploy from a branch.
5. Select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site.

## Important limitations
- This MVP does not call an AI model or promise business income.
- It does not collect payments or user accounts.
- Ledger data stays in the current browser/device and is not synced or backed up.
- Do not enter sensitive personal or payment information.
- Before charging customers, add a secure payment provider, server-side order verification, privacy policy, terms, refunds, and support contact.
- Keep API keys on a backend; never put secret keys in frontend JavaScript.

## Next milestone
Add a backend for accounts, saved plans, secure payments, and verified order status. Add an AI API only after validating demand and costs.
