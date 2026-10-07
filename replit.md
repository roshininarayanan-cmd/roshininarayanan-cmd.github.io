# Roshini Narayanan Portfolio

A static, root-level Jekyll portfolio for publishing directly through GitHub Pages.

## Run & operate

- `bundle install` — install the local GitHub Pages/Jekyll dependencies.
- `bundle exec jekyll serve` — preview at `http://127.0.0.1:4000`.
- GitHub Pages publishes from the `main` branch and `/(root)`; no separate build workflow is needed.

## Structure

- `index.md`, `about.md`, `work-experience.md`, `contact.md` — Markdown content with YAML front matter.
- `_config.yml` — site URL, empty `baseurl`, navigation, and supported GitHub Pages plugins.
- `_layouts/` and `_includes/` — shared page shell, metadata, navigation, and footer.
- `assets/css/site.css` — responsive, light-only styling; no JavaScript or external font dependencies.
- `PLAN.md` — approved scope; excluded from the published site.

## Project constraints

- Keep the published site at the repository root for the GitHub user site `roshininarayanan-cmd.github.io`.
- Keep personal content grounded in the supplied résumé. The email and LinkedIn are public; do not add the phone number.
- Do not add a web framework, backend, database, contact form service, tracking code, or package manager for a JavaScript app.
