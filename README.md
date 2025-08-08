
# Frontend Jobs Finder (Next.js, Pages Router)

Queries **public** ATS APIs (Greenhouse & Lever) for Frontend/React/UI roles via a safe proxy.
_No LinkedIn scraping._

## Quickstart
```bash
npm install
npm run dev
# open http://localhost:3000
```

## Deploy
1. Create a new GitHub repo and push this folder.
2. Import the repo in Vercel (or use `vercel` CLI) and deploy.

## Notes
- Extend `ALLOWLIST` in `pages/api/proxy.ts` to support more ATS vendors.
- The proxy adds caching headers to reduce load on ATS hosts.
