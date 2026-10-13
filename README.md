# LearnSmart AI

A responsive adaptive-learning MVP for Mathematics. This is a fresh, editable implementation inspired by the requirements shared in the project brief; it is **not the original source code exported from the Base44 website**.

## Features
- Student dashboard with topic strengths and weaknesses
- 10-question diagnostic quiz selected from a 30-question bank
- Rule-based recommendation engine
- Prerequisite-aware learning roadmap
- Practice questions with feedback and explanations
- Learning resources for five Mathematics topics
- Progress analytics
- Demo mode for judges
- Browser-local persistence using `localStorage`
- Responsive desktop and mobile layout

## Tech stack
React, TypeScript, Vite, Recharts, Lucide React, CSS.

## Run locally
Install Node.js 18+ then run:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```

## Deploy
Push this folder to GitHub, then import the repository into Vercel or Netlify. Build command: `npm run build`; output directory: `dist`.

## Notes
- This MVP uses local browser storage and demo data. It does not yet include account authentication or a shared database.
- For multi-user production use, add Supabase authentication, PostgreSQL tables, and row-level security.
- The recommendation logic is transparent and rule-based, not a trained AI model.
- Diagnostic scores are estimates based on a limited question bank and should not be treated as complete proof of mastery.
