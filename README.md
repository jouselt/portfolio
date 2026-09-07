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
- `llms.txt` — concise LLM-readable profile (discoverable via `<link rel="llms">`)
- `llms-full.txt` — extended LLM-readable full content
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

## Local preview

From this directory:

```bash
python3 -m http.server 4321 --bind 0.0.0.0
```

Then open:

- `http://localhost:4321/`
- or the machine's Tailscale/LAN URL if testing from another device
