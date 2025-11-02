# FullPack

[![npm version](https://img.shields.io/npm/v/fullpack.svg)](https://www.npmjs.com/package/fullpack)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/<your-username>/FullPack/issues)

**FullPack** is an open-source project generator that lets you build a complete full-stack web app — **frontend, backend, database, and DevOps** — in **under 2 minutes**.  
It’s optimized for speed, flexibility, and modern best practices.

---

## 📦 Installation (via npm)

You can use **FullPack** globally or on-demand.

### Option 1 — Run instantly with `npx` (recommended)
``` bash
npx fullpack init
```

Option 2 — Install globally
``` bash
npm install -g fullpack
fullpack init
```

## ✨ Features
``` bash
1. 2-Minute Setup: Spin up a complete project without leaving your editor.
2. Modular Design: Choose only what you need — backend, frontend, database, or devops.
3. Database Integration via CLI: Configure and connect databases directly from the terminal.
4. Optional DevOps Support: Enable Docker or Nginx with simple flags (e.g., --docker, --nginx).
5. Best Practices Built-In: Clean folder structures and modern tooling.
6. Open Source & Extensible: Add your favorite stacks or tools via pull requests.
```
---

📂 Folder Structure
``` bash
FULLPACK/
├── adapters/
│   ├── drizzle/
│   ├── prisma/
│   └── README.md
├── backend/
│   ├── javascript/
│   ├── python/
│   └── README.md
├── database/
│   ├── mongodb/
│   ├── mysql/
│   ├── postgres/
│   ├── sqlite/
│   └── README.md
├── devops/
│   ├── docker/
│   ├── nginx/
│   └── README.md
├── frontend/
│   ├── nextjs/
│   ├── reactjs/
│   └── README.md
└── cli.ts
```

⚙️ CLI Usage Examples
``` bash 
# Create a full project with Docker and PostgreSQL
npx fullpack init --frontend nextjs --backend javascript --db postgres --docker

# Minimal setup (React + SQLite)
npx fullpack init --frontend reactjs --db sqlite
```

CLI Flags
``` bash
| Flag         | Description               | Example              |
| ------------ | ------------------------- | -------------------- |
| `--frontend` | Choose frontend framework | `--frontend reactjs` |
| `--backend`  | Choose backend language   | `--backend python`   |
| `--db`       | Select database type      | `--db postgres`      |
| `--docker`   | Enable Docker setup       | `--docker`           |
| `--nginx`    | Enable Nginx setup        | `--nginx`            |
```

🧰 Local Development

To work on FullPack locally:
``` bash
# Clone the repo
git clone https://github.com/<your-username>/FullPack.git
cd FullPack

# Install dependencies
npm install

# Test the CLI locally
npm link
fullpack init --frontend reactjs --db sqlite

Unlink when done:
npm unlink -g fullpack
```
---

Philosophy:
``` bash
“Learn by building, contribute by improving.”

FullPack is not just a tool, it’s a collaborative effort to define what a clean, fast, and modern full-stack setup should look like.
We intentionally don’t include every technology. The goal is to build something solid and let the community expand it.
```
---

🤝 Contributing

Contributions are welcome 🙌

If you’re passionate about improving stack automation or adding support for new tech (e.g., NestJS, Redis, or FastAPI)
. check out our Contributing Guide

``` bash
1. Fork the repo
2. Create a new branch
    git checkout -b feature/add-nestjs
3. Commit your changes
    git commit -m "Add NestJS support"
4. Push and open a Pull Request 🚀
```
---

Roadmap
``` bash
 Backend: JavaScript, Python
 Frontend: React, Next.js
 Database: MongoDB, MySQL, PostgreSQL, SQLite
 DevOps: Docker, Nginx (toggleable flags)
 Support for Bun runtime
 Add FastAPI and NestJS templates
 Integrate CI/CD with GitHub Actions
 GUI for configuration (future)
```

🪄 License
MIT License © 2025 Atnatewos Hailealem


💬 Community
Join discussions, suggest ideas, or showcase your setups in the Discussions tab!
Let’s make full-stack development faster, cleaner, and more fun together!

FullPack: The fastest way to launch a full-stack app from your editor, in under 2 minutes.