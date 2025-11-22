# AI-Emergency-Assistant-
# PanicPulse — Frontend-only (GitHub Pages friendly)
This repo contains two pages:
- `index.html` — login / sign-up (stores user & contacts in `localStorage`)
- `emergency.html` — voice-activated emergency UI (uses annyang for speech
recognition)
>
**Important:** Twilio / SMS / Calls must be done from a secure backend. Do not
embed Twilio credentials in frontend code.
### Running locally
1. Clone repo or download files.
2. Open `index.html` in a browser (double-click or `Live Server` in VS Code).
### Deploy to GitHub Pages
1. Create a new repository on GitHub.
2. From your local folder:
```bash
git init
git add .
git commit -m "Initial commit — PanicPulse"
git branch -M main
git remote add origin <your-repo-URL>
git push -u origin main
