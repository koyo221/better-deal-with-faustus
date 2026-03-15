# PoE1 Currency Exchange Calculator

A tool for Path of Exile 1 players to compare whether buying an item with Divine Orbs or Chaos Orbs is more cost-effective.

**Live:** https://koyo221.github.io/poe-currency-tool/

## Features

- Set the current Divine-to-Chaos exchange rate
- Add multiple items and enter their prices in both Divine and Chaos (as fractions, e.g. 1/100 div)
- Instantly see which currency gives you a better deal and by how much
- Search currencies from a built-in list or add your own
- All inputs are saved to localStorage automatically

## Tech Stack

- React 19 + TypeScript
- Vite 8
- Tailwind CSS 4

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deployment

Deployed to GitHub Pages via GitHub Actions. Every push to `main` triggers a build and deploy automatically.
