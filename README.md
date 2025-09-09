# Pro Coder Starter

A clean, fast, **SEO‑optimized** starter by **n1s4t**. Perfect for portfolios, landing pages, and docs. Deploys to **GitHub Pages** automatically.

[![Deploy](https://img.shields.io/badge/Deploy-GitHub%20Pages-0ea5e9.svg)](https://github.com/n1s4t/pro-coder-starter/actions)
[![Made by n1s4t](https://img.shields.io/badge/Made%20by-n1s4t-111111.svg)](https://github.com/n1s4t)
[![guns.lol](https://img.shields.io/badge/guns.lol-n1s4t-111111.svg)](https://guns.lol/n1s4t)

---

## ✨ Features

- ⚡ **Instant**: static HTML + CSS, no build tools required
- 🔍 **SEO‑first**: Meta, OpenGraph, Twitter, **JSON‑LD**, robots, sitemap
- 🎨 **Design**: modern, dark‑mode friendly, responsive
- 🚀 **1‑click deploy**: GitHub Pages workflow included
- ♿ **Accessible**: skip link, semantic structure

---

## 🚀 Quickstart (copy & paste)

```bash
# 1) Download and unzip the project
#    (or use the ZIP from the ChatGPT message)

# 2) Initialize a new git repo
git init
git add .
git commit -m "feat: bootstrap Pro Coder Starter"

# 3) Create GitHub repo (named pro-coder-starter) and add remote
#    Replace <TOKEN> with a GitHub token or create repo via the UI.
#    If using the UI, just run the remote+push lines.
gh repo create n1s4t/pro-coder-starter --public --source . --remote origin --push

# If you don't use GitHub CLI, do this instead after creating repo in the UI:
# git remote add origin https://github.com/n1s4t/pro-coder-starter.git
# git branch -M main
# git push -u origin main
```

> After the first push, **GitHub Pages** will deploy automatically (see Actions tab).  
> Public URL: `https://n1s4t.github.io/pro-coder-starter/`

---

## 🛠️ Local preview

```bash
# Option A: Python (built-in on most systems)
python -m http.server 3000

# Option B: Node.js (if installed)
npx serve -p 3000

# Then open http://localhost:3000/pro-coder-starter/
```

---

## 🔧 Customize

- Edit `index.html` (titles, description, content)
- Replace social links; your guns.lol is already linked: **https://guns.lol/n1s4t**
- Swap images in `assets/` (favicon, OpenGraph, guns.lol icon)
- Update `site.webmanifest`, `sitemap.xml` and `robots.txt` if you change the repo name
- Upload a **Repo Social Preview** in GitHub Settings → Options (optional)

---

## 📈 SEO checklist

- Unique `<title>` and `<meta name="description">`
- Valid **Open Graph** and **Twitter** tags
- Correct canonical URL
- Sitemap & robots present
- **JSON‑LD** (`WebSite`) updated with your links
- Fast load: no render‑blocking resources

---

## 📜 License

Released under the **MIT License**.  
© 2025 **n1s4t**. All rights reserved.
