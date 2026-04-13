# aisafety.org.au

A minimal landing page for AI safety in Australia.

The site provides a definition of AI safety and links to key Australian and international organisations working on AI safety.

## Architecture

Single static HTML file (`index.html`). No build step, no framework, no JavaScript.

## Hosting

Hosted on Netlify with custom domain [aisafety.org.au](https://aisafety.org.au). Netlify auto-deploys from the `main` branch — the repo is published as-is, with no build command. See `netlify.toml`.

## Editing

Edit `index.html` directly. The definition section includes several commented-out alternative definitions that can be swapped in by uncommenting the desired option and commenting out the current one.

Outbound links and footer are also edited directly in `index.html`.

## Archive

`archive/site-content-2026-04.md` contains a flattened reference copy of the
previous Hugo/Wowchemy version of the site — kept in case any of the curated
links or framings are useful later.

## Licence

Content is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Maintained by [Alexander Saeri](mailto:zan@goodancestors.org.au), affiliated with the [Good Ancestors Project](https://goodancestors.org.au).
