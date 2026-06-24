# Should we correct the bias in Confidence Bands for Repeated Functional Data?

[![build and
publish](https://github.com/computorg/published-202606-devijver-scb/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202606-devijver-scb/actions/workflows/build.yml)
[![DOI:10.57750/nmyg-wg36](https://img.shields.io/badge/DOI-10.57750/nmyg--wg36-034E79.svg)](https://doi.org/10.57750/nmyg-wg36)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

[![](https://img.shields.io/badge/review-report-blue.png)](https://github.com/computorg/published-202606-devijver-scb/issues?q=is%3Aopen+is%3Aissue+label%3Areview)

### Authors

- [Emilie Devijver](https://lig-aptikal.imag.fr/~devijvee/) (CNRS, Univ.
  Grenoble Alpes, Grenoble INP, LIG, 38000 Grenoble, France)
- [Adeline Samson](http://adeline.e-samson.org) (Univ. Grenoble Alpes,
  CNRS, Grenoble INP, LJK, 38000 Grenoble, France)

### Abstract

While confidence intervals for finite quantities are well-established,
constructing confidence bands for objects of infinite dimension, such as
functions, is challenging. In this paper, we explore the concept of
parametric confidence bands for functional data with an orthonormal
basis. Specifically, we revisit the method proposed by Sun and Loader,
which yields confidence bands for the projection of the regression
function in a fixed-dimensional space. This approach can introduce bias
into the confidence bands when the dimension of the basis is
misspecified. Building on this insight, we introduce a corrected,
unbiased confidence band. Surprisingly, our corrected band tends to be
wider than that suggested by a naive approach. To address this, we
propose a model selection criterion that allows for data-driven
estimation of the basis dimension. The bias is then automatically
corrected after dimension selection. We illustrate these strategies
through an extensive simulation study. We conclude with an application
to real data.
