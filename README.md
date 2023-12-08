
![](images/zoo_banner.png)

## Why?

Parameter estimates are often hard to interpret substantively,
especially when they are generated by complex models with non-linear
components, interactions, or transformations. Instead of reporting
unintuitive parameters, data analysts would rather focus on simple
quantities of interest, which have straightforward scientific
interpretations. Unfortunately, meaningful estimands—and their standard
errors—are often tedious to compute, and the terminology used to
describe them varies tremendously across fields.

These problems are compounded by the fact that modeling packages produce
objects with very different structures and which hold different
information. This means that end-users often have to write customized
code to interpret the output of different models. This can lead to
wasted effort, confusion, and mistakes, and it can hinder the
implementation of best practices.

## What?

This online book introduces a conceptual framework and the
`marginaleffects` package for `R` and `Python`. This software can
facilitate the interpretation of [over 100 classes of statistical
models](https://marginaleffects.com/vignettes/supported_models.html),
including linear, GLM, GAM, mixed-effects, bayesian, categorical
outcomes, and more. With a single unified interface, users can compute
and plot many quantities of interest, including:

-   Predictions (aka fitted values or adjusted predictions)
-   Comparisons such as risk differences, risk ratios, odds, etc.
-   Slopes (aka marginal effects)
-   Marginal means
-   Linear and non-linear hypothesis tests
-   Equivalence tests
-   Uncertainty estimates using the delta method, bootstrapping,
    simulation, or conformal inference.
-   Much more!

[The Marginal Effects Zoo](https://marginaleffects.com/) is a free
online book with over 30 chapters of tutorials, case studies, and
technical notes. It covers a wide range of topics, including how the
`marginaleffects` package can facilitate the analysis of:

-   Experiments
-   Observational data
-   Causal inference with G-Computation
-   Machine learning models
-   Bayesian modeling
-   Multilevel regression with post-stratification (MRP)
-   Missing data
-   Matching
-   Inverse probability weighting
-   Conformal prediction

[Get started by clicking
here!](https://marginaleffects.com/vignettes/get_started.html)

## How to help

The `marginaleffects` package and the Marginal Effects Zoo book will
always be free. If you like this project, you can contribute in four
main ways:

1.  Make a donation to the [Native Women’s Shelter of
    Montreal](https://www.nwsm.info/) or to [Give
    Directly](https://www.givedirectly.org/), and send me (Vincent) a
    quick note. You’ll make my day.
2.  Submit bug reports, documentation improvements, or code
    contributions to the Github repositories of the [`R`
    version](https://github.com/vincentarelbundock/marginaleffects) or
    the [`Python`
    version](https://github.com/vincentarelbundock/pymarginaleffects) of
    the package.
3.  [Cite the `marginaleffects` package](CITATION.html) in your work and
    tell your friends about it.
4.  Create a new entry [for the Meme
    Gallery!](https://marginaleffects.com/vignettes/meme.html)

<a href="http://marginaleffects.com">
<img src="https://user-images.githubusercontent.com/987057/134899484-e3392510-2e94-4c39-9830-53356fa5feed.png" align="center" alt="marginaleffects logo" width="200" />
</a> <br><br>
<img src="https://github.com/vincentarelbundock/marginaleffects/workflows/R-CMD-check/badge.svg">
<img src="https://img.shields.io/badge/license-GPLv3-blue">
<a href = "https://marginaleffects.com" target = "_blank"><img src="https://img.shields.io/static/v1?label=Website&message=Visit&color=blue"></a>
<br><br>
