
<!-- README.md is generated from README.Rmd. Please edit that file -->

<!-- badges: start -->

[![Netlify
Status](https://api.netlify.com/api/v1/badges/d304fc5e-f2a0-48af-a5d8-111e78aadfe8/deploy-status)](https://app.netlify.com/sites/tylurp/deploys)
<!-- badges: end -->

This blog uses [blogdown](https://github.com/rstudio/blogdown),
[hugo-tanka](https://github.com/road2stat/hugo-tanka), and
[netlify](https://www.netlify.com/).

1.  blogdown: Creates blogs/websites in R with R Markdown
2.  hugo-tanka: A minimal hugo/blogdown theme
3.  netlify: Deployment, continuous integration and more for blog

There are two modifications made to the theme, they are:

1.  Uses font awesome icons for the header instead of text, currently
    configurable in `config.toml`. For example:

<!-- end list -->

``` toml
[[menu.main]]
    name = "fa fa-github"
    url = "https://github.com/tylurp"
    weight = 1
```

2.  Uses a different code highlight theme using highlight.js, currently
    not configurable in `config.toml` but can be modified in
    `header.html`, see
    [this](https://amber.rbind.io/blog/2017/11/15/syntax-highlighting/)
    post for more information.
