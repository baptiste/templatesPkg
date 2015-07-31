# templatesPkg
minimal package templates for R

## Motivation

Authoring an R package is easy; however, many new (and old) package developers face confusion when trying to submit their package to CRAN for wider dissemination. The rules and checks are strict, and this is a good thing to ensure quality, but it can cause a lot of confusion at first. While many guides and tools are available to help, there is a lack of truly minimal examples to follow as models. 

One will find here various minimal template packages -- `templateRcpp`, `templateRoxygen`, `templateKnitrVignette`, `templateTestthat`, each with dummy content but illustrating, correctly, a specific feature of the R package ecosystem. Since they are all mostly orthogonal, it should be easy to mix and match, e.g. adding a vignette to a package using `testthat`.

Too often issues arise following outdated guides, or mis-interpretation of WRE by new package developers; using existing packages as a model is not always practical either: many are just bad examples to follow, others are too obscure because of their specific content (irrelevant to learn about proper package structure).

## Disclaimer

This is just an idea at this stage. Don't trust any of the content for creating your own package.

## List of templates

- `templateBasic`: standard R package, illustrating `Depends:` `Imports:` and `Suggests:`
- `templateRoxygen`: using roxygen to generate documentation
- `templateKnitrVignette`: using knitr to create vignettes
- `templateTestthat`: 
- `templateRcpp`:

## Feature matrix

TODO: a matrix illustrating the features implemented (mostly diagonal, by construction). Elements could be: `demo`, `inst`, `vignette`, `tests`, `Imports`.

## Useful links

WRE
Hadley's book
package.skeleton
pkgKitten
whoami
devtools
roxygen
knitr
testthat
tools
Runits
etc.
