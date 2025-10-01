## Markdown Portfolio

A minimal Markdown-powered portfolio using GitHub Pages and the `jekyll-theme-primer` theme. Edit a few Markdown files and publish a clean personal site with no build pipeline required.

### Features
- Simple: author pages in Markdown (`.md`).
- Zero-config hosting on GitHub Pages.
- Clean default layout via Primer theme.

### Quick Start
1. Fork or clone this repository.
2. Update `_config.yml` with your site title and any options.
3. Edit `index.md` to add your content (bio, links, sections).
4. Push to the `master`/`main` branch and enable GitHub Pages in repository settings (Pages → Branch: `master`/`main`, folder: `/root`).

Once Pages finishes building, your portfolio is live at `https://<your-username>.github.io/<repo-name>/`.

### Repository Structure
- `_config.yml`: Jekyll site configuration (title, theme).
- `index.md`: Home page content using the theme’s default layout.
- `500.html`, `50x.html`: Generic error pages (optional).

You can add more pages by creating additional `.md` files at the repo root, for example `about.md` or `projects.md`. Set `layout: default` in the front matter to use the theme’s layout.

Example page file:

```
---
layout: default
title: Projects
---

# Projects

- Project Alpha — Short description and link
- Project Beta — Short description and link
```

### Local Preview (optional)
Preview the site locally with Jekyll (a `Gemfile` is included):

Prerequisites: Ruby and Bundler installed.

1. Install dependencies: `bundle install`
2. Serve locally: `bundle exec jekyll serve`
3. Open `http://localhost:4000` in your browser.

See `docs/local-development.md` for tips and troubleshooting.

### Customization Tips
- Theme: swap `jekyll-theme-primer` in `_config.yml` for another official theme.
- Navigation: add headings and links directly in your Markdown pages.
- Assets: create an `assets/` folder for images and reference them in Markdown.

### Contributing
Suggestions and improvements are welcome. See `CONTRIBUTING.md` for guidelines.

### License
No license file is included. If you plan to share or accept contributions, consider adding a LICENSE (e.g., MIT or Apache-2.0).
