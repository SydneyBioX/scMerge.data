scMerge.data
================

## Introduction

`scMerge.data` contains an illustrative data to demonstrate the utility
of the `scMerge` package. For more details, please see here:
<https://github.com/SydneyBioX/scMerge>.

This package is a convenient way to load the data stored
[here](http://www.maths.usyd.edu.au/u/yingxinl/wwwnb/scMergeData/sce_mESC.rda).

## Installation

`scMerge` is available on Bioconductor
(<https://bioconductor.org/packages/scMerge>). You can install it using:

``` r
# install.packages(c("BiocManager", "devtools"))

## Install scMerge from Bioconductor, requires R 3.6.0 or above
BiocManager::install("scMerge")
devtools::install_github("SydneyBioX/scMerge.data")
```

## Vignette

You can find the vignette at our website:
<https://sydneybiox.github.io/scMerge/index.html>.

## Case studies

You can find a list of case studies here:
<https://sydneybiox.github.io/scMerge/articles/>.

## Contact us

If you have any enquries, especially about performing `scMerge`
integration on your own data, then please contact
<bioinformatics@maths.usyd.edu.au>. You can also [open an
issue](https://github.com/SydneyBioX/scMerge/issues) on GitHub.

## Reference

**scMerge leverages factor analysis, stable expression, and
pseudoreplication to merge multiple single-cell RNA-seq datasets**

Yingxin Lin, Shila Ghazanfar, Kevin Y.X. Wang, Johann A. Gagnon-Bartsch,
Kitty K. Lo, Xianbin Su, Ze-Guang Han, John T. Ormerod, Terence P.
Speed, Pengyi Yang, Jean Y. H. Yang

Our manuscript published at PNAS can be found
[here](http://www.pnas.org/lookup/doi/10.1073/pnas.1820006116).
