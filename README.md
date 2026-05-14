# fated.ai

Static landing page for Fated AI. Hosted via GitHub Pages.

## Stack
- Plain HTML + CSS, no JS, no build step
- Karla via Google Fonts
- Animated SVG chart line as the hero accent
- Mobile responsive, respects `prefers-reduced-motion`

## Deploy
GitHub Pages serves `main` branch from `/`. Custom domain `fated.ai` is set via the `CNAME` file plus four `A` records at the registrar:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

## Edit
Just push to `main` and Pages will rebuild within ~1 minute.
