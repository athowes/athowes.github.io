# site

This is a personal website built with [Distill for R Markdown](https://rstudio.github.io/distill/).

## Deployment

The website is automatically built and deployed to GitHub Pages using GitHub Actions.
The workflow is triggered on every push to the `main` branch.

### Setup

To enable GitHub Actions deployment:

1. Go to your repository Settings → Pages
2. Under "Build and deployment", set the source to **GitHub Actions**
3. The workflow will automatically deploy the site on the next push to `main`

### Local Development

To build the site locally:

```r
# Install required packages
install.packages(c("rmarkdown", "distill"))

# Build the site
rmarkdown::render_site(encoding = 'UTF-8')
```

The built site will be generated in the `docs/` directory.
