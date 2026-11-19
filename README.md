# Pennylight — shine a light on every penny
Personal finance web app (Phase 1) by **Business Labs Software and Technology** · WhatsApp +234 905 390 3530

Static, no build step. Data stays in the user's browser (localStorage); backup/restore is Excel (.xlsx). The user picks a currency (NGN, GHS, XOF, XAF, KES, ZAR, USD, CAD, MXN, BRL, AUD, AED, INR, GBP, EUR); it is saved in the backup's *Setup & Guide* sheet.

## Languages
English, Français, Português, Español, العربية (right-to-left), Deutsch, हिन्दी (Hindi). On first launch the app reads the browser/OS language list (`navigator.languages`) and region, and pre-selects the language and currency in the welcome screen. Changeable any time in Settings. Excel backups keep English sheet names so they stay importable in any language.

## Categories
21 default categories plus up to 4 user-created custom ones (Settings → Categories). Any category can be hidden from lists.

## Deploy
1. Push this folder to a GitHub repo.
2. vercel.com → Add New Project → import the repo → Framework: **Other** → Deploy.

## Phase 2 (planned)
Investment advisor (real estate, stocks, crypto, agro-arbitrage) via serverless `/api` routes on Vercel + AI, using age, lifestyle and in-app analytics. Not financial advice.
