
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Intro to R Markdown

This repo contains an introductory presentation and exercises with R
Markdown.

The goal is to get users comfortable with the basic syntax and workflow
of writing (primarily academic) documents in R Markdown.

The presentation can be found in `presentations/learn-rmarkdown.Rmd`

Users will need a few packages to run the presentation

``` r
install.packages("rmarkdown")
install.packages("bookdown")
install.packages("xaringan")
```

You will also need a LaTeX installation. If you don’t already have one,
I recommend using tinytex

``` r
install.packages("tinytex")
tinytex::install_tinytex()  # install TinyTeX
```

Further instructions are available
[here](https://bookdown.org/yihui/rmarkdown/installation.html)

You will also need a reference manager for the examples. I personally
like [zotero](https://www.zotero.org/)
