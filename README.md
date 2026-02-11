# The Kitchen Journal

A recipe app that feels like flipping through an inherited cookbook — warm, unhurried, and personal.

## Why

This project is a test case for [frontend-craft](https://github.com/anthropics/skills), a merged Claude Code skill built from three sources:

- [anthropics/skills/frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) — aesthetic direction and expressive design
- [anthropics/skills/web-artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder) — practical tooling and tech stack
- [Dammyjay93/interface-design](https://github.com/Dammyjay93/interface-design) — deep craft methodology and self-evaluation

The merged skill combines domain exploration, intent-driven design, and systematic self-checks to produce interfaces that avoid generic AI aesthetics. This app was the first build using it — a proof that the methodology works end-to-end from direction to output.

## Design

Built with an editorial kitchen journal aesthetic:

- **Typography:** Playfair Display (headlines), Source Serif 4 (body), Caveat (handwritten accents)
- **Palette:** Aged parchment, terracotta, herb green, saffron — colors drawn from a real kitchen
- **Layout:** Asymmetric card grid with featured recipes at different scales
- **Depth:** Surface color shifts instead of shadows — like layers of worn paper

## Features

- **Category filtering** — browse by section (Breakfast, Mains, Sides, Soups, Desserts)
- **Search** — filter by recipe name, description, tags, or ingredients
- **Recipe detail** — slide-in panel with ingredients, numbered steps, and personal notes
- **Staggered page-load animation**
- **Responsive** — adapts from desktop to mobile

## Running

Open `index.html` in a browser. No build step, no dependencies.

## Stack

Single HTML file — vanilla HTML, CSS, and JavaScript. Fonts loaded from Google Fonts.
