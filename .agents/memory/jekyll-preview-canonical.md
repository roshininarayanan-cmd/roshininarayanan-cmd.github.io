---
name: Jekyll preview canonical URLs
description: Replit Jekyll development-server URLs can differ from production canonical metadata.
---

For this Replit Jekyll setup, do not use the development server’s SEO output to validate production canonical URLs. Running `jekyll serve` with `--host 0.0.0.0 --port 5000` can generate canonical tags and sitemap entries with the local origin even though `_config.yml` has the GitHub Pages URL. A normal production build honors the configured site URL.

**Why:** the local preview server overrides the URL it uses while serving, which is expected for development but misleading during SEO checks.

**How to apply:** use the live preview for visual and navigation checks, then run `JEKYLL_ENV=production bundle exec jekyll build` and inspect the generated canonical links and sitemap for GitHub Pages URLs.
