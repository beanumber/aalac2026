# AALAC 2026 Workshop

This repository contains the source code for the AALAC 2026 workshop website, built with [Quarto](https://quarto.org/).

## Website

The website is automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the main branch.

**Live site**: [https://beanumber.github.io/aalac2026/](https://beanumber.github.io/aalac2026/)

## Development

### Prerequisites

- [Quarto CLI](https://quarto.org/docs/get-started/)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/beanumber/aalac2026.git
   cd aalac2026
   ```

2. Render the website:
   ```bash
   quarto render
   ```

3. Preview the website locally:
   ```bash
   quarto preview
   ```

### Project Structure

- `_quarto.yml` - Quarto configuration file
- `index.qmd` - Homepage content
- `about.qmd` - About page content
- `styles.css` - Custom CSS styles
- `.github/workflows/publish.yml` - GitHub Actions workflow for deployment

## Contributing

To add new content or make changes:

1. Edit the appropriate `.qmd` files
2. Test locally with `quarto preview`
3. Commit and push changes to the main branch
4. The site will automatically rebuild and deploy via GitHub Actions
