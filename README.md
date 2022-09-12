
# quarto-revealjs-uaz

<!-- badges: start -->
<!-- badges: end -->

The goal of quarto-revealjs-uaz is to make a template for Quarto revealjs slides with University of Arizona branding (fonts, colors, logos, images, etc.)

## Installation

To use this theme, first install it from GitHub using the following shell command:

``` bash
quarto install extension cct-datascience/quarto-revealjs-uaz
```

This will create a `_extensions` folder in your working directory with the necessary resources in it. Then, use `uaz-revealjs` as the format.

```yml
---
title: "Presentation"
author: "Your Name"
format: uaz-revealjs
---
```

If you'd also like to install the template .qmd file, you can instead use:

``` bash
quarto use template cct-datascience/quarto-revealjs-uaz

```

## Notes on how to make your own theme:

- [Making Quarto extensions](https://quarto.org/docs/extensions/formats.html)
- [Rladies theme extension](https://github.com/beatrizmilz/quarto-rladies-theme)
- [Customizing Scss for slide themes](https://quarto.org/docs/presentations/revealjs/themes.html#creating-themes)
- [Creating an R-Ladies quarto format](https://www.visibledata.co.uk/posts/2022-07-29_creating-an-r-ladies-quarto-format/)

