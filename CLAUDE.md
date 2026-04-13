# CLAUDE.md

Guidance for Claude Code when working in this repository.

## What this is

A single-file static landing page for [aisafety.org.au](https://aisafety.org.au).
One HTML file, inline CSS, no JavaScript, no build step, no framework.

## Structure

- `index.html` — the entire site. Contains inline `<style>`, page content,
  commented-out alternative definitions, links, and footer.
- `netlify.toml` — minimal Netlify config (publish from repo root, no build).
- `archive/site-content-2026-04.md` — flattened reference copy of the previous
  Hugo/Wowchemy version of the site. Not served; kept for reference only.
- `README.md`, `LICENSE`, `LICENSE.md` — repo docs and licence.

## Editing

Edit `index.html` directly. To swap definitions, uncomment the desired option in
the definition block and comment out the current one. Don't introduce a build
step, CSS framework, or JavaScript — the whole point of the current design is
minimalism.

## Deployment

Netlify auto-deploys from `main`. There is no build command — Netlify publishes
the repo root as-is. Custom domain `aisafety.org.au` is configured in the
Netlify dashboard.

## Do not

- Add a build step, `package.json`, or `node_modules/`.
- Add JavaScript, analytics, or tracking.
- Add a CSS framework (Tailwind, Bootstrap, etc.).
- Split into multiple HTML files.
- Restore Hugo, Wowchemy, or any static site generator.
