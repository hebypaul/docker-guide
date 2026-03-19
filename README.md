<div align="center">

# 🐳 Docker — The Complete Developer Guide

**A professional, single-page reference for fullstack developers.**  
Everything from first principles to production deployment — in one clean, dark-themed document.

[![Live Site](https://img.shields.io/badge/Live%20Site-hebypaul.github.io%2Fdocker--guide-0db7ed?style=flat-square&logo=docker&logoColor=white)](https://hebypaul.github.io/docker-guide/)
[![HTML](https://img.shields.io/badge/Built%20with-HTML%20%2F%20CSS%20%2F%20JS-e34c26?style=flat-square&logo=html5&logoColor=white)](https://hebypaul.github.io/docker-guide/)
[![License](https://img.shields.io/badge/License-MIT-3fb950?style=flat-square)](LICENSE)

![Docker Guide Preview](https://hebypaul.github.io/docker-guide/site-preview.png)

</div>

---

## 📖 About

This is a **self-contained, offline-capable HTML reference guide** for Docker — built as a single `index.html` file and hosted on GitHub Pages. No frameworks, no build step, no backend. Just open it and read.

It was written for fullstack web developers who need a reliable, well-organized reference across the full Docker lifecycle: from writing a `Dockerfile` to running a production Swarm stack.

**The guide covers:**

- Core concepts — images, containers, volumes, networks, registries
- `Dockerfile` — every instruction explained with examples
- Build optimization — layer caching, BuildKit, secret mounts
- Multi-stage builds — real Node.js + React example
- Docker Compose — full production `docker-compose.yml` with healthchecks, profiles, and override files
- Volumes & Networking — named volumes, bind mounts, tmpfs, all network drivers
- Registries — Docker Hub, GHCR, AWS ECR, multi-platform builds with `buildx`
- CI/CD — GitHub Actions workflow (build → test → push)
- Deployment — SSH context, Docker Swarm, rolling updates
- Security — non-root users, capability dropping, read-only filesystems, Docker Scout
- Debugging — exec, logs, inspect, stats, `docker debug`, system cleanup
- Full command cheatsheet — organized by category

---

## 🌐 Live Site

> **[hebypaul.github.io/docker-guide](https://hebypaul.github.io/docker-guide/)**

---

## ✨ Features

| Feature | Detail |
|---|---|
| 📋 Copy buttons | Every code block has a hover-reveal copy button |
| 🧭 Active TOC | Sidebar highlights the current section as you scroll |
| 🔗 Smooth anchors | All TOC links scroll smoothly with accurate offsets |
| ⬆️ Back to top | Fixed button fades in after scrolling, returns to top |
| 🎨 Dark theme | Full dark UI with custom-styled scrollbars |
| 📱 Responsive | Sidebar collapses on mobile; tables scroll horizontally |
| ♿ Accessible | Semantic HTML, `aria-label` on nav and buttons |
| 🔍 SEO-ready | Open Graph + Twitter Card meta tags for link previews |
| ⚡ Zero deps | No framework, no build tool — pure HTML/CSS/JS |

---

## 🗂️ Structure

```
docker-guide/
├── index.html      # The entire guide — single self-contained file
└── README.md       # This file
```

The whole site lives in one file. Fonts are loaded from Google Fonts (Inter + JetBrains Mono). Everything else — layout, syntax highlighting, copy buttons, scroll behavior — is hand-written CSS and vanilla JS.

---

## 🚀 Running Locally

No setup required. Just open the file:

```bash
# Clone the repo
git clone https://github.com/hebypaul/docker-guide.git
cd docker-guide

# Open directly in your browser
open index.html         # macOS
xdg-open index.html     # Linux
start index.html        # Windows
```

Or serve it with any static server:

```bash
npx serve .
# → http://localhost:3000
```

---

## 🛠️ Deployment

The site is deployed via **GitHub Pages** from the root of the `main` branch.

To update the live site, just push changes to `main`:

```bash
git add index.html
git commit -m "docs: update docker compose section"
git push origin main
```

GitHub Pages picks up the change automatically — usually live within 60 seconds.

**Settings path:** `Repository → Settings → Pages → Source: Deploy from branch → main / (root)`

---

## 📋 Sections at a Glance

| # | Section | What You'll Learn |
|---|---|---|
| 1 | Core Concepts | Images, containers, volumes, networks, registries |
| 2 | Installation & Setup | Docker Desktop, Engine, context switching |
| 3 | Images | Pull, inspect, tag, save, prune |
| 4 | Containers | Run flags, lifecycle, exec, logs, inspect, stats |
| 5 | Dockerfile Deep-Dive | Every instruction — FROM to SHELL |
| 6 | Build Optimization | Layer caching, BuildKit, cache mounts, secret mounts |
| 7 | Multi-Stage Builds | Reduce image size; Node + React example |
| 8 | Volumes & Storage | Named volumes, bind mounts, tmpfs |
| 9 | Networking | Bridge, host, overlay, macvlan; port publishing |
| 10 | Environment & Config | ENV, ARG, --env-file; secret hygiene |
| 11 | Docker Compose | Full production `docker-compose.yml` |
| 12 | Compose Patterns | Override files, profiles, scaling |
| 13 | Registries & Pushing | Docker Hub, GHCR, ECR, multi-platform buildx |
| 14 | CI/CD | GitHub Actions: build → push pipeline |
| 15 | Deployment | SSH context, Docker Swarm, rolling updates |
| 16 | Security | Non-root, cap-drop, read-only fs, Docker Scout |
| 17 | Debugging | exec, logs, diff, stats, system prune |
| 18 | Command Cheatsheet | Quick-reference tables for every category |

---

## 🤝 Contributing

Spotted an outdated command, a missing flag, or a section that could be clearer? Contributions are welcome.

1. Fork the repo
2. Edit `index.html` directly
3. Open a pull request with a short description of the change

Please keep the single-file structure — no build tools, no external JS bundles.

---

## 📄 License

MIT — free to use, share, or adapt. Attribution appreciated but not required.

---

<div align="center">

Made by [Heby Paul](https://github.com/hebypaul)

</div>
