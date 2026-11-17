**Author:** 
João Henrique Porfirio Firmiano ([@joaohpf](https://github.com/joaohpf))

# AIA Systems — Website

Institutional website for **AIA Systems**: websites, automations and integrations for businesses.

## Highlights
- **3D scroll scene (Three.js):** a laptop that opens, spins 360° and becomes a project showcase with arrows, zoom and project details.
- **About us:** animated headline and a neon sign version of the logo (SVG + CSS).
- **Contact "order terminal":** visitors build an order that prints as a thermal receipt; submissions are emailed via [Web3Forms](https://web3forms.com).
- **Accessibility panel:** reduce motion, larger text and high contrast (saved per browser).
- Instagram and WhatsApp links, responsive layout and on-demand rendering for performance.

## Tech
HTML, CSS and vanilla JavaScript in a single `index.html`, with Three.js loaded from a CDN (jsDelivr). No build step.

## Run locally
Open `index.html` in a browser, or serve the folder:
```bash
npx serve .
```

## Deploy
Static site: import the repository on **Vercel** (framework preset: *Other*, no build command) or enable **GitHub Pages** on the `main` branch.

> The Web3Forms access key in `index.html` is public by design; it only allows sending form submissions to the company inbox.
