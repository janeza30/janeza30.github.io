# Julio Añez — Portfolio

Personal portfolio site built with Next.js 16, Tailwind CSS v4, and Framer Motion. Deployed via GitHub Pages as a static export.

## Stack

- **Next.js 16** — App Router, static export (`output: "export"`)
- **Tailwind CSS v4** — Utility-first styling
- **Framer Motion** — Scroll-triggered animations
- **TypeScript** — Type safety throughout
- **Lucide React** — Icon library

## Sections

- **Hero** — Name, title, bio, CTA buttons, social links
- **About** — Profile photo, background, tech stack tags, YouTube embed
- **Projects** — PacMan, Eye Exercise, Real Time Bus Tracker
- **Contact** — Email CTA, GitHub / LinkedIn / Email cards

## Development

The source lives in the `portfolio-redesign/portfolio/` directory (not tracked in this repo). This repo contains the compiled static export deployed to GitHub Pages.

To make changes, edit the source project and rebuild:

```bash
cd portfolio-redesign/portfolio
npm install
npm run dev        # local dev server at localhost:3000
npm run build      # generates the out/ folder
```

Then copy the contents of `out/` into this repo, commit, and push.

## Live Site

[https://janeza30.github.io](https://janeza30.github.io)

## Contact

- GitHub: [@janeza30](https://github.com/janeza30)
- LinkedIn: [linkedin.com/in/janeza](https://www.linkedin.com/in/janeza/)
- Email: julio_anez_ayala@outlook.com
