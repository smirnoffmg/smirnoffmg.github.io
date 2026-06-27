# Maksim Smirnov — Personal Site

Portfolio / CV site for [smirnoffmg.dev](https://smirnoffmg.dev), built with Jekyll and deployed via GitHub Pages.

Да, я пишу себе документацию, эта привычка сильнее меня :)

## Project Structure

- `_config.yml` — site configuration (author, URL, analytics, remote theme)
- `_data/cv.yml` — CV data; edit this to update resume content
- `index.html` — main page (self-contained HTML with inline styles)
- `_layouts/default.html` — base HTML layout
- `404.md` — custom 404 page
- `cv_ptl.pdf` — downloadable PDF resume
- `favicon.svg` — site favicon

## Local Development

1. **Install dependencies** (first time only):
   ```sh
   bundle install
   ```

2. **Run the dev server with live reload:**
   ```sh
   bundle exec jekyll serve --livereload
   ```
   Site available at [http://localhost:4000](http://localhost:4000).

> **Note:** Changes to `_config.yml` require a server restart — Jekyll only reads config at startup.

## Deployment

Pushes to `main` deploy automatically via GitHub Pages.
