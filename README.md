# Bug Tracker Pro

Full-stack Jira-lite clone built with React + Express + MongoDB.

Server: `server/` — Node.js, Express, Mongoose, JWT
Client: `client/` — React, Vite, Tailwind (optional), Chart.js

Quick start

1. Backend

- Copy `.env.example` to `.env` and set `MONGO_URI` and `JWT_SECRET`.
- Install and run server:

```powershell
cd server
npm install
npm run dev
```

2. Frontend

```powershell
cd client
npm install
npm run dev
```

Notes

- The frontend expects the API at `http://localhost:4000/api`.
- Tailwind requires PostCSS/Vite setup; the project includes a basic `tailwind.config.cjs`.

