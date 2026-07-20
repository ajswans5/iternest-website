# Friday — Start Here

This repository is the new canonical home for the IterNest public website.

## Goal

Build a clean, warm, mobile-first company website that explains IterNest clearly and makes the founder journey easy to follow.

## Existing decisions to preserve

- Keep the existing IterNest logo and brand direction.
- The visual experience should feel calm, warm, hopeful, minimal, and professional.
- Avoid a corporate, crowded, or overly technical presentation.
- The public navigation should include:
  - Home
  - Products
  - Journal
  - About
  - Contact
- Permanent supporting pages should include:
  - Privacy
  - 404
- The homepage should feature the newest journal entry near the top.
- Only the newest journal entry needs to appear on the homepage; older entries belong in the Journal archive.
- The journal may be presented publicly as **From the Nest**, while the navigation label remains **Journal** for clarity.
- Keep destinations distinct:
  - Products leads to product information.
  - Journal leads to the journal index.
  - Follow the Journey leads to contact or future signup behavior.
- Contact email: `hello@iternest.app`

## Initial product areas

The company website should be able to introduce:

1. IterNest for Homeschool
2. IterNest for Entrepreneurs
3. MoneyMap

These are connected by one philosophy: understand the situation first, then help people make informed decisions with less cognitive load.

## Content architecture

- `content/journal/` contains source copy and metadata for journal posts.
- `content/pages/` contains source copy for permanent pages.
- `src/pages/` contains page implementations.
- `src/components/` contains reusable UI.
- `src/styles/` contains shared styles and design tokens.
- `public/assets/` contains static assets.
- `docs/` contains implementation, deployment, and editorial notes.

## Implementation constraint

Do not redesign the product brands or invent a new company identity without approval. Choose the lightest implementation that supports fast journal publishing, good mobile performance, accessibility, and Cloudflare deployment.
