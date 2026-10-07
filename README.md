# Roshini Narayanan — Portfolio

A static Jekyll portfolio designed for GitHub Pages. All site content and Jekyll files live at the repository root; there is no application framework, backend, database, contact form service, or tracking code.

## Publish with GitHub Pages

1. Name the GitHub repository `roshininarayanan-cmd.github.io`.
2. Push the files in this repository root to the `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.

GitHub Pages builds the Jekyll site directly from the branch. No separate build workflow is needed. `_config.yml` uses the user-site URL and an empty `baseurl`.

## Update the site

- Edit `index.md`, `about.md`, `work-experience.md`, or `contact.md` to update page content. Keep the YAML front matter at the top of each file.
- Shared navigation and footer content live in `_includes/`; the page shell is in `_layouts/default.html`.
- Update colors, typography, and responsive styling in `assets/css/site.css`.
- The contact email is public and uses a `mailto:` link. The phone number is intentionally not included.
- `PLAN.md` records the approved site scope and is excluded from the published site.

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`. Jekyll rebuilds the site as you edit Markdown, layouts, includes, or CSS.

## Run Lighthouse

With the local preview running, open `http://127.0.0.1:4000` in Chrome. Open DevTools → **Lighthouse**, choose **Desktop** or **Mobile**, and run a report. Review Performance, Accessibility, Best Practices, and SEO; the target for each is 90 or higher.
