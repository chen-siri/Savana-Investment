# Savana 招商官网

## Project Overview
Static website for Savana — a fast-fashion shopping APP targeting India and Middle East markets. This is a merchant recruitment (招商) landing page for attracting suppliers in women's clothing, accessories, and beauty categories.

## Tech Stack
- Pure HTML/CSS/JS (no build tools, no frameworks)
- Single-page static site (`index.html` is the main page)
- `savana-standalone.html` is an alternate/extended version
- Deployed via Vercel

## Project Structure
```
index.html              — Main recruitment landing page (730 lines, self-contained)
savana-standalone.html  — Standalone extended version (2860 lines)
savana-logo*.png        — Logo assets (various formats)
素材/                    — Design assets and generated images
```

## Deployment
```bash
# Preview
npx vercel --yes --name savana-website

# Production
npx vercel --prod --yes --name savana-website
```

## Design System
- Colors: Black (#0A0A0A) primary, Gold accent (#F5B12D)
- Chinese font stack: PingFang SC, Hiragino Sans GB, Microsoft YaHei, Noto Sans SC
- Border radius tokens: --r-sm (8px) through --r-pill (999px)
- All styles are inline in the HTML files (no external CSS)

## Language
- UI and content are in Chinese (zh-CN)
- Code comments can be in English or Chinese
