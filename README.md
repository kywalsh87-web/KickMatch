# KickMatch PWA

KickMatch is a progressive web app (PWA) for grassroots football management.
It includes Fixtures, Tournaments, and a Referee Marketplace with map and radius filtering.

## Features
- Fixtures: Add, search, assign referees.
- Tournaments: Add, view tournaments.
- Referees: Add availability, assign to fixtures, map visualization.
- PWA support: Installable on phones, offline caching.
- Export / Import JSON for sharing and backup.

## Setup & Deploy

### Local
```bash
npm install
npm run dev
```

### Deploy to Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. From the project root: `vercel --prod`
3. Your app will be live at the generated Vercel URL.

### GitHub + One-Click Deploy
1. Push this repository to GitHub.
2. Go to Vercel → Import Project → GitHub → select this repo.
3. Deploy instantly with one-click.
