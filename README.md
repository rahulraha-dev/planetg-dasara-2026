# Planet G Dasara 2026 Gift Game

Cloudflare Worker for Planet G – The Mobile Gallery.

## Routes
- `/staff` — Staff Portal
- `/customer` — Customer Portal
- `/play` — Customer Portal alias
- `/api/health` — Health check

## Deploy
Cloudflare Workers Builds should use:
- Build command: leave blank
- Deploy command: `npx wrangler deploy`
- Root directory: `/`
- Production branch: `main`
Deployment connected to Cloudflare Workers
