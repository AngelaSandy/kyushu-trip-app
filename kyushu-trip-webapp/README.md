Kyushu Trip — Ready-to-deploy Web App (PWA)
===========================================

What I generated for you:
- Vite + React project using your KyushuTripApp UI
- Firebase integration (use .env to provide keys)
- PWA manifest + icons
- vercel.json for quick deployment

Quick start (local)
-------------------
1. Copy `.env.example` to `.env` and fill values (we already included your Firebase keys in the example)
2. Run:
   npm install
   npm run dev
3. Open http://localhost:5173

Deploy to Vercel
----------------
1. Create a Vercel account (if you don't have one).
2. Create a new project from this repository (or upload the zip).
3. Add the same environment variables in the Vercel Project Settings (matching names in .env).
4. Deploy — Vercel will run `npm install` and `npm run build`.

Notes
-----
- If VITE_API_KEY is not present, the app runs in offline/demo mode (local-only).
- For friends to use the real-time split, they must open the deployed site (and Firestore rules must allow reads/writes for your project or use authenticated rules).
