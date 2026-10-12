# POLAC Research Hub

A frontend-only React + TypeScript research workspace for the topic **“Effectiveness of Social Media Usage on the Academic Performance of POLAC Cadets.”**

## Run locally

Requirements: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

For a production build:

```bash
npm run build
npm run preview
```

## Features

- Responsive overview dashboard and charts (Recharts)
- Questionnaire creation and response editing
- Response search, sample/user record filters, and deletion
- CSV export
- Sample records to preview the experience
- Browser `localStorage` persistence
- Settings to hide demo data or clear local records

## Important data note

The included sample records are illustrative demo data only. They are not real POLAC cadet responses and must not be presented as findings. This prototype has no server or database. Records are stored only in the current browser profile and do not sync across devices. Export collected data regularly. The charts are descriptive and do not establish causation.
