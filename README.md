# Academic Portfolio Site

Static single-page academic profile built with [Jekyll](https://jekyllrb.com/) for GitHub Pages deployment.

## Getting Started

```bash
bundle install
bundle exec jekyll serve
```

The site will be available locally at `http://127.0.0.1:4000/`. Changes to markdown, data, and assets reload automatically.

## Customize Your Content

- Update `_data/profile.yml` with your name, affiliation, short bio, `photo`, and curated social links (use the provided IDs: `linkedin`, `google-scholar`, `dblp`, `github`).
- Set `_config.yml` → `url` (e.g., `https://your-github-username.github.io`) and `baseurl` (leave empty for user sites or `/your-repo` for project sites) before deployment so canonical links and the sitemap resolve correctly.
- Add recent items to `_data/news.yml` (most recent first).
- Curate publications in `_data/publications.yml`; include `link` or `doi` for direct access.
- Adjust colors or layout in `assets/css/main.scss`.

## Deploy to GitHub Pages

1. Commit the source files to a GitHub repository.
2. In **Settings → Pages**, set the branch to `main` (or `master`) and directory to `/ (root)`.
3. GitHub Pages runs Jekyll automatically using the bundled `github-pages` gem.

Search engines can discover the site via the generated `sitemap.xml`; verify indexing by adding the deployed URL in Google Search Console and submitting the sitemap.

Optional: Add a `CNAME` file at the project root if you plan to use a custom domain.
