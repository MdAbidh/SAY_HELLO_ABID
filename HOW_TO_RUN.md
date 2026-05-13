# 🚀 HOW TO RUN — Abid Hossain Portfolio

## Quick Start (30 seconds)

### Option 1: Python (No Install Needed)
```bash
cd portfolio
python3 -m http.server 8080
```
Open: http://localhost:8080

### Option 2: Node.js
```bash
cd portfolio
npx serve .
```
Open: http://localhost:3000

### Option 3: VS Code Live Server
1. Install "Live Server" extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

---

## Deploy to GitHub Pages (Free Hosting)

```bash
# 1. Initialize git
git init && git add . && git commit -m "Portfolio launch 🚀"

# 2. Create repo on github.com, then:
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git branch -M main && git push -u origin main

# 3. Go to: GitHub Repo → Settings → Pages → Source: main / root
# 4. Live in 2-3 minutes at: https://YOUR_USERNAME.github.io/portfolio/
```

## Files Overview
| File | Purpose |
|------|---------|
| `index.html` | Fast landing page |
| `app/index.html` | Full portfolio (all 8 sections) |
| `css/style.css` | Shared styles |
| `images/profile.jpg` | Your profile photo |
| `404.html` | GitHub Pages redirect |
| `README.md` | Full documentation |
