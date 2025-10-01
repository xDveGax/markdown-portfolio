## Local Development

You can preview the site locally using Jekyll. This mirrors how GitHub Pages builds your site.

### Prerequisites
- Ruby (2.7+ recommended)
- Bundler (`gem install bundler`)

### Setup
1. Install dependencies (a `Gemfile` is included):
   ```bash
   bundle install
   ```
2. Serve the site:
   ```bash
   bundle exec jekyll serve
   ```
3. Open `http://localhost:4000`.

### Common Issues
- Missing gems: run `bundle install` and ensure the `Gemfile` matches above.
- Caching problems: stop the server and run `bundle exec jekyll clean`.
- Theme not applied: ensure `_config.yml` includes `theme: jekyll-theme-primer`.

### Project Structure Notes
- Add additional pages as `*.md` files at the root, with front matter:
  ```yaml
  ---
  layout: default
  title: About
  ---
  ```
- Store images in `assets/` and reference them in Markdown: `![alt](assets/img.png)`.
