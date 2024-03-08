
# University of Arizona Themed Revealjs Extension for Quarto

<!-- badges: start -->
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
<!-- badges: end -->

`uaz-revealjs` is a template for Quarto revealjs slides with University of Arizona branding (fonts, colors, and logo.)

## Installation

To use this theme, first install it from GitHub using the following shell command:

``` bash
quarto add cct-datascience/uaz-revealjs
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
quarto use template cct-datascience/uaz-revealjs
```

## Notes on how to make your own theme:

- [Making Quarto extensions](https://quarto.org/docs/extensions/formats.html)
- [Rladies theme extension](https://github.com/beatrizmilz/quarto-rladies-theme)
- [Customizing Scss for slide themes](https://quarto.org/docs/presentations/revealjs/themes.html#creating-themes)
- [Creating an R-Ladies quarto format](https://www.visibledata.co.uk/posts/2022-07-29_creating-an-r-ladies-quarto-format/)

