# site

This is a personal website built with [Distill for R Markdown](https://rstudio.github.io/distill/).

## Deployment

The website is automatically built and deployed to GitHub Pages using GitHub Actions.
The workflow is triggered on every push to the `master` branch.

### Local Development

To build the site locally:

```r
# Install required packages
install.packages(c("rmarkdown", "distill"))

# Build the site
rmarkdown::render_site(encoding = 'UTF-8')
```

The built site will be generated in the `docs/` directory.
