# MRMR

Linear models for analysing non-life runoff reserves, generalizing the multiplicative chain ladder and additive models, with visual and statistical diagnostics.

Compatibility updates by Renova.

Version 0.1.4.9001: two class tests compare only the first class (`class(x)[1L]`), as current R requires a length-one `if()` condition: in `OriginPeriodFromYears()` (`R/CreateOriginPeriods.R`) and `LatestDiagonal()`. The DESCRIPTION gains `Authors@R` for the existing author.

## Install

```r
install.packages("MRMR", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

See the [R-universe package page](https://renova-r.r-universe.dev/MRMR) for builds and installation. This release is tagged on GitHub as `renova-0.1.4.9001`:

```r
remotes::install_github("renova-r/MRMR@renova-0.1.4.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

MRMR is by Brian A. Fannin; the original CRAN package is at <https://CRAN.R-project.org/package=MRMR>. License: GPL (>= 2); see [COPYING](COPYING). The original README is kept as [README.upstream.md](README.upstream.md).
