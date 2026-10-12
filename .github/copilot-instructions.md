# Dhanvin Pharmaceuticals Website

## Project
- Build a static corporate website with Astro, semantic HTML, CSS, and minimal JavaScript.
- Keep the company name exactly as `Dhanvin Pharmaceuticals`.
- Do not add ecommerce, accounts, backend services, databases, prices, inventory, or unsupported business claims.
- Current supply: quality medicines and surgical products to the Government of Andhra Pradesh. Do not add unprovided institutions, tenders, contract details, or certifications.
- Describe international import/export as a future ambition, not current activity.
- Keep the enquiry form frontend-only; it prepares an email and does not store or transmit data.

## Development
- Use Node.js 22.19 or newer with npm.
- Install dependencies with `npm install`.
- Run locally with `npm run dev` (default URL: `http://localhost:4321`).
- Verify production output with `npm run build`.
- Keep shared page structure in `src/components/` and `src/layouts/`; global design rules belong in `src/styles/global.css`.
- Preserve keyboard access, responsive layouts, useful metadata, and reduced-motion support.

## Launch checklist
- [x] Astro project scaffolded in this workspace.
- [x] Company website pages and reusable components implemented.
- [x] Contact links and frontend-only enquiry flow added.
- [x] No additional VS Code extensions required.
- [x] Production build succeeds.
- [x] Local development server started.
- [x] README documents local development and build commands.
- [x] Privacy information and website terms routes added.

## Before production
- Have the privacy and website terms information reviewed for production use.
- Confirm the final domain before configuring canonical metadata or a sitemap.
- Confirm the supplied business details remain current.
- Do not configure GitHub, Azure, or deployment unless requested.
