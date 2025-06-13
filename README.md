
# 🚀 Dev Blog — Developer Blogging Platform

A lightning-fast, SEO-optimized developer blog built with **Next.js**, **Strapi (Headless CMS)**, and **PostgreSQL**. Built with scalability, content flexibility, and modern developer workflows in mind — all within a powerful **monorepo** structure using `pnpm`.

## ✨ Features

- 🧠 Headless CMS with Strapi for flexible content modeling
- ⚡ Blazing fast frontend with Next.js 14 App Router
- 💾 PostgreSQL for a robust relational database layer
- 🧱 Clean monorepo architecture using pnpm workspaces
- 🧩 Modular, maintainable, and developer-first structure
- 🔍 Fully SEO-optimized (OpenGraph, dynamic metadata, clean URLs)
- 🛡️ Type-safe, RESTful APIs and future GraphQL-ready
- 📱 Responsive design & performance-focused UI (Framer Motion + Tailwind)

---

## 🏗️ Tech Stack

| Layer        | Tech                  |
|--------------|------------------------|
| Frontend     | Next.js (App Router)  |
| Backend      | Strapi Headless CMS   |
| Database     | PostgreSQL             |
| Package Mgr  | pnpm (monorepo setup) |
| Styling      | Tailwind CSS          |
| Animations   | Framer Motion         |
| Hosting (Planned) | Vercel + Railway/Render |

---

## 🔧 Project Structure

```
/apps
  ├── frontend     # Next.js frontend
  └── backend      # Strapi backend

/pnpm-workspace.yaml
/package.json      # root
```

This structure allows clear separation of concerns, modular development, and faster onboarding.

---

## 🚀 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/dev-blog.git
   cd dev-blog
   ```

2. **Install dependencies**  
   ```bash
   pnpm install
   ```

3. **Setup environment variables**  
   Create `.env` files for both `apps/frontend` and `apps/backend` (examples coming soon).

4. **Run dev servers**
   ```bash
   pnpm dev
   ```

---

## 📌 Roadmap

- [x] Phase 1: Monorepo + Backend setup with PostgreSQL
- [ ] Phase 2: Frontend scaffold + CMS integration
- [ ] Phase 3: SEO, Markdown rendering, rich editor
- [ ] Phase 4: Deploy to production, add analytics & sitemap

---

## 🤝 Contributing

Wanna help? Suggestions, issues, and PRs are all welcome! Just follow the contribution guide (coming soon).

---

## 📄 License

MIT — feel free to fork and build your own flavor of a dev blog. Just don’t forget to deploy it 🚀

---

## 🙌 Shoutout

Built with 💻 by [Deepesh](https://github.com/deepeshjaindj) — follow for more fullstack goodness.

