# Maksim Smirnov CV Site

This is a personal CV/portfolio site built with Jekyll and a remote Harvard-style CV theme.

Да, я пишу себе документацию, эта привычка сильнее меня :)

## Local Development

To preview and develop the site locally:

1. **Install dependencies** (first time only):
   ```sh
   bundle install
   ```

2. **Run the local server and watch for changes:**
   ```sh
   bundle exec jekyll serve --livereload
   ```
   - The site will be available at [http://localhost:4000](http://localhost:4000)
   - The server will automatically reload when you save changes to your files.

## LiveReload Feature

- **LiveReload** automatically refreshes your browser when you edit most files (content, data, etc.).
- **To use LiveReload:**
  1. Start the server with `--livereload` (see above).
  2. Open [http://localhost:4000](http://localhost:4000) in your browser.
  3. Edit your files and see changes instantly.
- **_config.yml changes:**
  - If you change `_config.yml`, you must manually restart the server:
    1. Stop the server (`Ctrl+C` in terminal).
    2. Run `bundle exec jekyll serve --livereload` again.
  - This is because Jekyll only reads configuration at startup.

## Project Structure
- `_config.yml` — Site configuration
- `_data/cv.yml` — CV data (edit this to update your resume)
- `index.md` — Main page
- `404.md` — Custom 404 page

## Notes
- The site uses a remote theme: `smirnoffmg/harvard-style-cv-theme`
- No need to install or manage the theme manually; it is pulled automatically.

## Deployment
- The site is designed for GitHub Pages, but you can use any static hosting provider.
