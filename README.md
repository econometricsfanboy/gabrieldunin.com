# gabrieldunin.com

Static source for https://www.gabrieldunin.com.

## Structure

- `docs/_config.yml`: site metadata and Jekyll configuration
- `docs/_layouts/`: shared page layouts
- `docs/_includes/`: reusable partials
- `docs/_posts/`: blog posts
- `docs/assets/`: images and other static assets
- `.github/workflows/pages.yml`: GitHub Pages build and deploy workflow

## Local development

1. Install Ruby and Bundler.
2. `cd docs`
3. `bundle install`
4. `bundle exec jekyll serve --livereload`

The local server will usually be available at `http://127.0.0.1:4000`.

## Deployment

The repository is set up for GitHub Pages. The workflow in
`.github/workflows/pages.yml` builds the Jekyll site from `docs/`.

If you switch the repository's Pages source to GitHub Actions, keep the custom
domain configured in the repository's Pages settings or via the GitHub API.
