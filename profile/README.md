<div align="center">

<img src="https://oaforge.vercel.app/logo.webp" alt="OAForge Logo" width="80" height="80" style="border-radius: 16px;" />

<br />
<br />

# OAForge

**AI-powered Online Assessment preparation — tailored to your role, your company, your JD.**

[![Live](https://img.shields.io/badge/Live-oaforge.vercel.app-5E6AD2?style=flat-square&logo=vercel&logoColor=white)](https://oaforge.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)](./LICENSE)
[![Built with React](https://img.shields.io/badge/Built%20with-React%20%2B%20TypeScript-61DAFB?style=flat-square&logo=react&logoColor=white)](https://oaforge.vercel.app)
[![AI](https://img.shields.io/badge/AI-Groq%20%2F%20LLaMA%203.3-f59e0b?style=flat-square)](https://groq.com)

</div>

---

## What is OAForge?

OAForge is a platform that generates **custom Online Assessment tests** based on your target role and company. Paste a job description → AI builds your assessment plan → practice with fresh, AI-generated questions → get a detailed score report.

Most OA prep platforms give you the same static question bank. OAForge generates questions on demand so you never run out of practice material — and every test is tailored to what your actual company tests.

---

## How It Works

```
1. Enter your target role + company (+ optional JD text)
        ↓
2. AI generates a custom section plan (DSA, DBMS, Aptitude, etc.)
        ↓
3. Review and customize sections before starting
        ↓
4. Take a timed test — answers auto-saved as you go
        ↓
5. Submit → instant score report + email breakdown
```

---

## Features

| Feature | Description |
|---|---|
| 🧠 **AI Assessment Plans** | Section plans tailored to your role and JD |
| ⚡ **Parallel Question Generation** | All sections generated simultaneously |
| ⏱️ **Timed Tests** | Countdown timer with auto-save |
| 📊 **Score Reports** | Per-section accuracy with weak area breakdown |
| 📧 **Email Reports** | HTML score report delivered to your inbox |
| 🔧 **Custom Sections** | Add your own sections beyond AI suggestions |
| 🔑 **BYOK** | Bring your own Groq API key |
| 🌙 **Dark / Light Mode** | Full theme support |

---

## Tech Stack

- **React 18** + TypeScript + Vite
- **TailwindCSS v4** + shadcn/ui
- **Framer Motion** — animations & transitions
- **TanStack Query** — server state management
- **React Hook Form** + Zod — forms & validation
- **React Router v6** — client-side routing

---

## Getting Started

```bash
git clone https://github.com/OAForge/oaforge-frontend
cd oaforge-frontend
npm install
cp .env.example .env    # add VITE_BACKEND_URL
npm run dev
```

---

## Contributing

Contributions are very welcome! OAForge is actively being improved and there are plenty of ways to help.

### Ways to Contribute

- 🐛 **Bug Reports** — found something broken? [Open an issue](https://github.com/OAForge/oaforge-frontend/issues/new?template=bug_report.md)
- 💡 **Feature Requests** — have an idea? [Start a discussion](https://github.com/OAForge/oaforge-frontend/issues/new?template=feature_request.md)
- 🎨 **UI / Design** — improve layout, responsiveness, accessibility, or animations
- 🔧 **Code** — fix bugs, refactor, or implement new features
- 📝 **Docs** — improve README, add code comments, or write guides

### How to Submit a PR

```bash
# 1. Fork the repo and clone your fork
git clone https://github.com/YOUR_USERNAME/oaforge-frontend

# 2. Create a feature branch
git checkout -b feat/your-feature-name

# 3. Make your changes and commit
git commit -m "feat: describe what you changed"

# 4. Push and open a pull request
git push origin feat/your-feature-name
```

### Good First Issues

Looking for a place to start? Check issues tagged [`good first issue`](https://github.com/OAForge/oaforge-frontend/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) — these are smaller, well-scoped tasks ideal for first-time contributors.

### UI Contribution Guidelines

- Match the existing design system (indigo `#5E6AD2` accent, dark/light token pairs)
- Keep components consistent with the Dashboard and existing pages
- Test on both dark and light mode before submitting
- Mobile responsiveness is required for any UI changes

> Not sure if your idea fits? Open an issue first and we'll discuss it before you write any code.

---

## Author

Built by **OAFORGE TEAM**


---

<div align="center">

**OAForge · [oaforge.vercel.app](https://oaforge.vercel.app) · Ace Every OA**

</div>
