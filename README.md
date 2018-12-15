# BUSpaRse notebooks

This repository has example notebooks that demonstrate how to go from fastq files to sparse matrices for scRNA-seq data from start to end. To run the notebooks, please install [kallisto](https://pachterlab.github.io/kallisto/starting), [bustools](https://github.com/BUStools/bustools), and the [BUSpaRse](https://github.com/BUStools/BUSpaRse) R package. 

## Installation of BUSpaRse
You can install BUSpaRse with:

``` r
if (!require(devtools)) install.packages("devtools")
devtools::install_github("BUStools/BUSpaRse")
```

This is work in progress. The package will be available on Bioconductor shortly.

Installation note: This package contains compiled code. MacOS users using R 3.5 should download and install Clang 6.0 and gfortran 6.1 compilers from [this webpage](https://cran.r-project.org/bin/macosx/tools/). R 3.5 no longer works with Clang 4, which was used for R 3.4.

## Notebooks

1. [10x v2 chemistry - 1k 1:1 Mixture of Fresh Frozen Human (HEK293T) and Mouse (NIH3T3) Cells](https://bustools.github.io/BUS_notebooks_R/10xv2.html)
2. [10x v3 chemistry - 1k 1:1 Mixture of Fresh Frozen Human (HEK293T) and Mouse (NIH3T3) Cells](https://bustools.github.io/BUS_notebooks_R/10xv3.html)

Notebooks for Drop-seq and CEL-seq2 are coming soom.
