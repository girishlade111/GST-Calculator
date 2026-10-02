# GST Calculator

A modern, client-side GST (Goods and Services Tax) calculator for Indian businesses, freelancers and shoppers. Enter an amount, pick a GST slab, and instantly see the tax-inclusive or tax-exclusive price with a clear breakup of CGST/SGST or IGST.

## Features

- Add-GST and Remove-GST modes (price exclusive → inclusive, or inclusive → exclusive)
- GST slabs: 0%, 5%, 12%, 18%, 28%
- Instant calculation with animated result card
- Dark glassmorphism UI styled with Tailwind CSS
- 100% client-side — no data leaves your browser, works offline after first load
- Responsive, mobile-friendly layout

## Tech Stack

- HTML5, vanilla JavaScript (single-file app)
- Tailwind CSS (CDN), Google Fonts (Inter)

## Quick Start

No build step, no dependencies.

```bash
git clone https://github.com/girishlade111/GST-Calculator.git
cd GST-Calculator
# open index.html in a browser, or serve it:
npx serve .
```

Or just visit the live demo: https://girishlade111.github.io/GST-Calculator/

## Project Structure

```
GST-Calculator/
├── index.html   # Full app: UI + styles + calculator logic
└── README.md
```

## Deploy

Static site. Deploy anywhere: GitHub Pages, Cloudflare Pages, Netlify, Vercel — or any static file host.

---

Built by Girish Lade · https://ladestack.in
