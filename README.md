# Cynthia Paiva Madruga

Personal portfolio site for GitHub Pages, built with Jekyll and semantic HTML, modern CSS, and a small vanilla JavaScript menu.

The default site language is English (`/`). Portuguese is available at `/pt/` and German at `/de/`. Shared page structure lives in `_includes/homepage.html`; translated homepage copy lives in `_data/homepage.yml`.

## Local preview

Install Jekyll using the current Ruby toolchain, then run:

```sh
bundle exec jekyll serve --livereload
```

The site is deployed automatically from `master` by [`.github/workflows/pages.yml`](.github/workflows/pages.yml).

The site intentionally has no JavaScript or CSS framework dependency. This keeps the page fast, resilient, and easy to maintain while preserving responsive behavior and accessibility support such as keyboard focus states and reduced-motion preferences.
