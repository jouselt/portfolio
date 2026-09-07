# Jouselt A. Fernández Portfolio

Recruiter-facing portfolio for Jouselt A. Fernández: Senior Fullstack Developer
(Angular / NestJS) + applied AI engineering.

Live site: https://jouselt.github.io/portfolio/

## Overview

This repo contains a static single-page portfolio focused on:

- proof-first presentation
- recruiter-friendly navigation
- enterprise delivery credibility
- applied AI workflow depth
- mobile-safe, accessible reading

The site is intentionally simple: `index.html` + `assets/css/main.css` + static assets.

## Current positioning

Use this repo to present Joe as:

- **Senior Fullstack Developer (Angular / NestJS)**
- **Applied AI engineering**
- **10 years of professional experience**

Do not reintroduce the old legacy positioning about "3 years frontend".

## Key files

- `index.html` — portfolio page
- `assets/css/main.css` — site styles
- `assets/docs/joe_fernandez.pdf` — current public resume PDF
- `assets/img/joe.jpg` — profile photo
- `robots.txt` — crawler rules
- `sitemap.xml` — sitemap for the canonical site URL

## Brand palette

- Background `#EDEADD`
- Green `#1C9C87`
- Pink `#EF7B84`
- Grey `#43485F`

## Portfolio skill

This repo ships a portfolio skill at:

- `skills/professional-fullstack-dev-portfolio/SKILL.md`

That skill is the portfolio-specific instruction source for rebuilds and revisions.
It uses:

- `skills/professional-fullstack-dev-portfolio/references/joe-profile.md`
- `/home/joe/dev/career-prep/CV_Jouselt_Fernandez.md`
- `/home/joe/ai-job-search/cv/main.tex`
- `/home/joe/ai-job-search/cv/main_cl.tex`

as the main identity and CV references.

## Local preview

From this directory:

```bash
python3 -m http.server 4321 --bind 0.0.0.0
```

Then open:

- `http://localhost:4321/`
- or the machine's Tailscale/LAN URL if testing from another device
