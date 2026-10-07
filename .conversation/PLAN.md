# Portfolio Site Plan

## Site

A responsive, accessible, single-column personal portfolio for Roshini Narayanan, published as a GitHub user site at `roshininarayanan-cmd.github.io`. The complete Jekyll site will live at the repository root, use Markdown pages with YAML front matter, and have an empty `baseurl` so URL filters work on GitHub Pages.

## Pages and content

- **Home:** concise introduction to Roshini's product-management focus across healthcare, enterprise software, and AI.
- **About:** MBA and biomedical engineering education, leadership, skills, and interests.
- **Work Experience:** résumé-based roles and accomplishments at GE HealthCare, Flexan, and Medtronic.
- **Contact:** public email via `mailto:` and LinkedIn profile.

Content will stay separate from reusable Jekyll layouts and includes. No achievements, employers, clients, metrics, or projects will be added beyond the supplied résumé. The supplied phone number will not be published.

## Design and implementation

Use a light-only palette, professional and warm typography, and a minimalist feminine feel with restrained color informed by the supplied Tower28 Beauty and ColourPop references. Use semantic HTML, accessible contrast, responsive plain CSS, and minimal JavaScript. Include navigation, a footer, SEO tags, a sitemap, a favicon, `_config.yml`, and a README with update, local preview, and Lighthouse instructions.

## Assumptions

- GitHub username: `roshininarayanan-cmd`; site URL: `https://roshininarayanan-cmd.github.io`.
- The supplied résumé is the source of truth for portfolio content; no personal information will be fetched from URLs.
- The email address and LinkedIn URL may be public. The phone number is omitted.
- The site will be published by GitHub Pages from the `main` branch and repository root, with no separate app, backend, database, or framework.

## Verification

Confirm the Jekyll site structure is directly in the project root and configured for GitHub Pages. Check navigation and responsive layouts at 375px and 1280px, and run Lighthouse against the built site where the available environment permits.
