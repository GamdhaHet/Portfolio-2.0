# Game Developer Portfolio

A premium, production-ready portfolio template for game developers. Built with React, Vite, TypeScript, Tailwind CSS, Framer Motion, and Lucide Icons.

Inspired by AAA game studio aesthetics — dark theme, neon glow accents, glassmorphism, cinematic animations, and immersive interactions.

## Quick Start

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Customize Your Portfolio

**All content lives in one file:** [`src/data/portfolio.ts`](src/data/portfolio.ts)

Edit this file to update:
- Name, bio, tagline, avatar
- Skills, tech stack, projects
- Experience, education, certificates, achievements
- Social links and contact details
- Navigation items and SEO meta tags

No need to touch component files for content changes.

### Images

- Place project images in `public/projects/`
- Update image paths in `portfolio.ts` (e.g. `/projects/neon-drift.jpg`)
- Add your avatar to `public/avatar.jpg`
- Add resume to `public/resume.pdf`
- Replace `public/og-image.png` for social sharing

### Colors & Theme

Colors are defined in [`src/styles/globals.css`](src/styles/globals.css) as CSS variables and in the Tailwind `@theme` block. Update `--primary`, `--secondary`, `--accent`, etc. to match your brand.

### Deployment URL

Update `meta.url` in `portfolio.ts` with your deployed domain for SEO and Open Graph tags.

## Build for Production

```bash
npm run build
npm run preview
```

## Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | UI framework |
| Vite 7 | Build tool |
| TypeScript | Type safety |
| Tailwind CSS 4 | Styling |
| Framer Motion | Animations |
| Lucide React | Icons |
| react-helmet-async | SEO meta tags |

## Project Structure

```
src/
├── components/
│   ├── ui/          # Button, Badge, Card, Modal, ProgressBar
│   ├── layout/      # Navbar, Footer, Container, SectionWrapper
│   └── effects/     # MouseGlow, Particles, TiltCard, ScrollReveal
├── sections/        # Hero, About, Skills, Projects, etc.
├── data/
│   └── portfolio.ts # ← EDIT THIS FILE
├── types/
│   └── portfolio.ts
├── hooks/
└── styles/
    └── globals.css
```

## Features

- Fully responsive design
- Dark gaming aesthetic with neon glow
- Glassmorphism UI elements
- Mouse glow cursor effect
- Animated gradient backgrounds & particles
- Typing animation in hero
- Scroll reveal animations
- 3D card tilt on project hover
- Project category filtering with modal details
- Sticky navbar with active section indicator
- Mobile-friendly navigation drawer
- Accessible (keyboard nav, ARIA, reduced motion)
- SEO optimized with JSON-LD structured data
- Lazy-loaded sections for fast initial load

## License

MIT — use freely for personal and commercial portfolios.
