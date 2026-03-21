# MWS Claude AI Platform — Resource Hub

Internal reference hub for the McDermott Will & Schulte Claude AI platform rollout.

## Files

- `index.html` — Hub/jump page linking all guides
- `MWS_Claude_Governance_Standard_v0.9.html`
- `MWS_Claude_Technical_Architecture_v1.0.html`
- `MWS_Claude_Delivery_Automation_v1.0.html`
- `MWS_Claude_Solution_Handoff_v1.0.html`
- `MWS_Claude_QA_Automation_v1.0.html`

## Deploy to Railway

### Option A — GitHub (recommended)
1. Push this folder to a GitHub repo (can be private)
2. Go to railway.app → New Project → Deploy from GitHub repo
3. Select the repo — Railway auto-detects Node.js and deploys
4. Done. Share the Railway URL.

### Option B — Railway CLI
```bash
npm install -g @railway/cli
railway login
railway init
railway up
```

### Option C — Drag and drop
Railway supports direct folder upload at railway.app/new

## Local preview
```bash
npm install
npm start
# Open http://localhost:3000
```
