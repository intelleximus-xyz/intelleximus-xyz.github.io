# intelleximus-xyz.github.io
Humanorum

## Jekyll Site with Navigation

This repository contains a Jekyll-based GitHub Pages site with a basic navigation template.

### Local Development

1. Install Jekyll and Bundler:
   ```bash
   gem install jekyll bundler
   ```

2. Build the site:
   ```bash
   jekyll build
   ```

3. Serve the site locally:
   ```bash
   jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser

### Adding New Pages

1. Create a new `.md` file in the root directory
2. Add front matter:
   ```yaml
   ---
   layout: default
   title: Your Page Title
   ---
   ```
3. Add your content using Markdown
4. Update the navigation in `_config.yml`:
   ```yaml
   navigation:
     - title: Your Page
       url: /your-page.html
   ```

### Structure

- `_config.yml` - Site configuration and navigation menu
- `_layouts/default.html` - Main layout template
- `_includes/navigation.html` - Navigation component
- `index.md` - Home page
- `about.md`, `blog.md`, `contact.md` - Sample pages

