# Mariana Fernandez Interior Design Website

A professional Jekyll website showcasing interior design services and portfolio.

## Local Development

To run this site locally:

1. Install Jekyll and dependencies:
   ```bash
   bundle install
   ```

2. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Visit `http://localhost:4000` in your browser

## Site Structure

- **Homepage** (`index.md`) - Professional landing page with service overview
- **About** (`about.md`) - Background, experience, and design philosophy  
- **Portfolio** (`portfolio.md`) - Project showcase with photo gallery structure
- **Services** (`services.md`) - Detailed service offerings and process
- **Contact** (`contact.md`) - Contact information and project inquiry form

## Adding Portfolio Images

1. Add images to `assets/images/portfolio/`
2. Update `portfolio.md` with image references
3. Images will display in responsive grid layout

## Customization

- **Colors/Styling**: Edit `assets/css/style.scss`
- **Site Config**: Update `_config.yml`
- **Navigation**: Modify `header_pages` in `_config.yml`

## GitHub Pages Deployment

This site is configured for GitHub Pages deployment. Simply push changes to the main branch and GitHub Pages will automatically build and deploy the site.

## SEO Features

- Configured with jekyll-seo-tag for optimal search engine optimization
- Professional meta descriptions and titles
- RSS feed support via jekyll-feed

## Contact Information

Update the contact information in:
- `_config.yml` (author section)
- `contact.md` (contact details)

---

Built with Jekyll and hosted on GitHub Pages.
