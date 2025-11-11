# site

This is a personal website built with [Distill for R Markdown](https://rstudio.github.io/distill/).

## Deployment

The website is automatically built and deployed to GitHub Pages using GitHub Actions. The workflow is triggered on every push to the `main` branch.

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

## Resources

* [get-blogging/](https://www.rostrum.blog/2020/02/27/get-blogging/)
* [lithium-metadata/](https://www.rostrum.blog/2019/09/06/lithium-metadata/)
* [google-analytics](https://matteocourthoud.github.io/post/website/#google-analytics)
* [socialize-your-blogdown/](https://xvrdm.github.io/2017/10/23/socialize-your-blogdown/)
* [Google search performance](https://search.google.com/search-console?resource_id=https%3A%2F%2Fathowes.github.io%2F)
* [Google Analytics](https://analytics.google.com/analytics/web/#/report-home/a139624638w200445539p194664841)
* [How to install Disqus on Hugo?](https://portfolio.peter-baumgartner.net/2017/09/10/how-to-install-disqus-on-hugo/)