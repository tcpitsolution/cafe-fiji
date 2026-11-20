# Brazilian Café — Premium React/Vite site

A responsive frontend for a Brazilian-inspired café in Nadi, Fiji. Menu content and price fields are deliberately placeholders; supplied review excerpts are included. No actual café contact or social handles are invented.

## Run locally
1. Install Node.js (18+ recommended).
2. In this folder run `npm install`.
3. Run `npm run dev` and open the local Vite URL.
4. Build for deployment: `npm run build`.

## Configure business details
Edit `src/config.js` and fill in confirmed values for phone, email, WhatsApp (digits only, with country code), Instagram, Facebook, Google Reviews, and Maps URLs.

## Configure actual menu
Edit `menuItems` in `src/main.jsx`. Replace illustrative names, photos, and `price: null` with the café's approved products and prices. Cart intentionally avoids calculating a fabricated total; WhatsApp message asks the café to confirm pricing and order availability.

## Deploy
Import the project into Vercel. Framework preset: Vite. Build command: `npm run build`. Output directory: `dist`.
