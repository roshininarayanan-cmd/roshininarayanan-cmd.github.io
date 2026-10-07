# Roshini Narayanan — portfolio

A static Jekyll site for a GitHub Pages user site. All pages, templates, styles, and assets live at the repository root.

## Local preview

Requirements: Ruby and Bundler.

```sh
bundle install
bundle exec jekyll serve
```

Jekyll prints the local preview address. Build without starting the preview server with:

```sh
bundle exec jekyll build
```

## Publish with GitHub Pages

1. Name the GitHub repository `roshininarayanan-cmd.github.io`.
2. Push this repository’s `main` branch.
3. In **Settings → Pages**, select **Deploy from a branch**, choose `main`, and select `/(root)`.
4. Save. GitHub Pages builds this Jekyll site directly; no GitHub Actions workflow or manual build step is needed.

The configured user-site URL is `https://roshininarayanan-cmd.github.io/`. `_config.yml` intentionally sets `baseurl: ""`; internal links and assets use Jekyll’s `relative_url` filter.

## Content and design

- Edit `index.md`, `about.md`, `work-experience.md`, and `contact.md` for page copy.
- Edit `_data/experience.yml` to update roles and achievements.
- Edit `_data/navigation.yml` to update site navigation.
- Edit `assets/css/styles.css` for styling.
- Shared HTML belongs in `_layouts/` and `_includes/`.

Personal and career information comes only from the résumé supplied for this site. The public contact page links to LinkedIn; it does not publish a phone number or email address.

## Lighthouse and responsive checks

Preview the site, open Chrome DevTools, and run Lighthouse for Performance, Accessibility, Best Practices, and SEO. The target is 90 or higher for each category. Use device emulation to check at 375px and 1280px widths.
