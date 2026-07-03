# Halim — Portfolio

Personal portfolio of **Abdelhalim Msbah** — Full-Stack Developer (Node.js, NestJS, React, React Native).

Static site (Next.js export). Deployed on Vercel.

## Structure

- `index.html` — homepage (animated hero, about, projects, contact)
- `projects/` — project case-study pages
  - `virexeg/` — VirexEG, full-stack production website for a clothing brand
  - `nova-luxury/` — Nova Luxury Furniture, full-stack e-commerce platform
  - `quran-yutla/` — Quran Yutla, AI-powered learning platform (NestJS + PostgreSQL)
- `_next/` — build assets (JS, CSS, fonts, media)

## Run locally

Serve the folder from any static server (absolute `/_next/...` paths require a web root, not `file://`):

```bash
npx serve .
```

Then open the printed local URL.
