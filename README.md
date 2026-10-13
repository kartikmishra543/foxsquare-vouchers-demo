# Foxsquare Vouchers — Vercel Demo

This package contains the latest enhanced static demo and original logo.
No React build or npm install is required for the website itself.

## Deploy from Windows PowerShell
Open a terminal inside this folder (the folder containing index.html and vercel.json).

```powershell
npx vercel login
npx vercel --prod
```

Allow npx to install Vercel CLI if asked. Complete login in your browser.
Choose your Vercel account, create a new project named foxsquare-vouchers-demo,
and use ./ as the project directory. Framework: Other. No build command.
Output directory: . (configured in vercel.json).
The CLI prints the production URL when deployment completes.

If the project has deployment protection enabled, check its settings so your
intended audience can access the production demo.

## Alternative: GitHub import
Upload these files to a new GitHub repository. Import it in Vercel.
Framework preset: Other. Root directory: repository root.
The included vercel.json supplies build and output settings.

## Demo behavior
FoxBot and video generation are simulated. Payments and emails are not sent.
My Gifts is stored locally in the visitor's browser. The current design loads
Tailwind, Lucide, fonts and catalog imagery from external services.
