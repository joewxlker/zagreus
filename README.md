# Zagreus

Zagreus is a privacy-centric, cross-chain token swap and bridge application focused on ultra-low fees and community rewards. Powered by a modern web stack and enhanced with deep crypto integration, Zagreus empowers users to swap, bridge, and earn — all with complete privacy.

## ✨ Features

- ⚡ Zagswap: A custom privacy swap engine that routes and masks transactions.
- 🔐 Privacy-first: Reverse proxy token swaps to obscure sender/receiver info.
- 🌉 Cross-Chain: Supports 300+ chains and over 1000+ tokens.
- 💰 Lowest Fees: Just 1% swap fee — one of the lowest available.
- 🎁 Zagshare & Zagpoints: Rewards ecosystem using NFTs and participation points.
- 🖥️ Fully Responsive UI: Built with Tailwind CSS, Next.js App Router, and animated transitions.
- 📄 Informational Resources: Includes links to docs, whitepaper, and roadmap.

## 🚀 Getting Started

1. Clone the repository

   git clone https://github.com/joewxlker/zagreus
   cd zagreus

2. Install dependencies

   npm install
   # or
   yarn install

3. Configure environment variables

   Copy .env.example to .env and fill in required fields like:

   NEXT_PUBLIC_DAPP_URL=https://your-dapp-url

4. Run the app

   npm run dev
   # or
   yarn dev

   Then open http://localhost:3000 in your browser.

## 🧱 Built With

- Next.js (App Router)
- Tailwind CSS
- TypeScript
- Vercel Hosting
- Custom animations and SVG effects
- Token + Chain logos from SimpleSwap CDN

## 📁 Project Structure Highlights

- app/page.tsx: Main homepage, including hero section, swap interface, and animated sections.
- components/SwapDisplay.tsx: Custom token swap UI with ETH/USDC visuals.
- public/tokens/: Token icons for visualized chains.
- env.ts: Used to safely access environment variables.

## 🔗 Live Demo

👉 https://zagreus.vercel.app/

## 👋 Author

[@joewxlker](https://github.com/joewxlker) — open for feedback and collaboration!
