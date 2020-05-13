
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ipa

<!-- badges: start -->

[![License:
MIT](https://img.shields.io/badge/license-MIT-blueviolet.svg)](https://opensource.org/licenses/MIT)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
<!-- badges: end -->

Convert character vectors between
[IPA](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet) and
[X-SAMPA](https://en.wikipedia.org/wiki/X-SAMPA) phonetic
representations.

## Installation

You can install the development version of **ipa** from GitHub with:

``` r
install_github("rossellhayes/ipa")
```

## Usage

``` r
sampa("/aI pi: \"eI/")
```

/aɪ piː ˈeɪ/

``` r
sampa(c("/\"nom.b4e/", "/nO~bR/"))
```

/ˈnom.bɾe/, /nɔ̃bʁ/

``` r
ipa("/aɪ piː ˈeɪ/")
```

`/aI pi: "eI/`

``` r
ipa(c("/ˈnom.bɾe/", "/nɔ̃bʁ/"))
```

`/nom.b4e/`, `/nO~bR/`

<!-- `ipa()` does not work in Rmarkdown, but does work in the console -->

-----

Please note that **ipa** is released with a [Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
