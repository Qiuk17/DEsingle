# DEsingle

*Zhun Miao*

*2018-06-19*

[![build](https://bioconductor.org/shields/build/release/bioc/DEsingle.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/DEsingle/)
[![platform](https://bioconductor.org/shields/availability/3.7/DEsingle.svg)](https://bioconductor.org/packages/release/bioc/html/DEsingle.html#archives)
[![downloads](https://bioconductor.org/shields/downloads/DEsingle.svg)](https://bioconductor.org/packages/release/bioc/src/contrib/DEsingle_1.0.3.tar.gz)

[![Source Package](data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxNi4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+DQo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IuWbvuWxgl8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgd2lkdGg9IjEzMXB4IiBoZWlnaHQ9IjIwcHgiIHZpZXdCb3g9IjAgMCAxMzEgMjAiIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDEzMSAyMCIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+DQo8ZGVmcz4NCgk8ZmlsdGVyIGlkPSJBZG9iZV9PcGFjaXR5TWFza0ZpbHRlciIgZmlsdGVyVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4PSIwIiB5PSIwIiB3aWR0aD0iMTMxIiBoZWlnaHQ9IjIwIj4NCgkJPGZlQ29sb3JNYXRyaXggIHR5cGU9Im1hdHJpeCIgdmFsdWVzPSIxIDAgMCAwIDAgIDAgMSAwIDAgMCAgMCAwIDEgMCAwICAwIDAgMCAxIDAiLz4NCgk8L2ZpbHRlcj4NCjwvZGVmcz4NCjxtYXNrIG1hc2tVbml0cz0idXNlclNwYWNlT25Vc2UiIHg9IjAiIHk9IjAiIHdpZHRoPSIxMzEiIGhlaWdodD0iMjAiIGlkPSJhIj4NCgk8cGF0aCBmaWxsPSIjRkZGRkZGIiBmaWx0ZXI9InVybCgjQWRvYmVfT3BhY2l0eU1hc2tGaWx0ZXIpIiBkPSJNMywwaDEyNWMxLjY1NiwwLDMsMS4zNDMsMywzdjE0YzAsMS42NTYtMS4zNDQsMy0zLDNIMw0KCQljLTEuNjU3LDAtMy0xLjM0NC0zLTNWM0MwLDEuMzQzLDEuMzQzLDAsMywweiIvPg0KPC9tYXNrPg0KPGcgbWFzaz0idXJsKCNhKSI+DQoJPHBhdGggZmlsbD0iIzU1NTU1NSIgZD0iTTAsMGg3MHYyMEgwVjB6Ii8+DQoJPHBhdGggZmlsbD0iIzE4ODFDMiIgZD0iTTcwLDBoNjF2MjBINzBWMHoiLz4NCgkNCgkJPGxpbmVhckdyYWRpZW50IGlkPSJTVkdJRF8xXyIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSItMjEzMS45NjE5IiB5MT0iNDEuMDUxOCIgeDI9Ii0yMTMxLjk2MTkiIHkyPSI0Mi4wNTE4IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEzMSAwIDAgMjAgMjc5MzUyLjUgLTgyMS4wMzEzKSI+DQoJCTxzdG9wICBvZmZzZXQ9IjAiIHN0eWxlPSJzdG9wLWNvbG9yOiNCQkJCQkI7c3RvcC1vcGFjaXR5OjAuMSIvPg0KCQk8c3RvcCAgb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjojMDAwMDAwO3N0b3Atb3BhY2l0eTowLjEiLz4NCgk8L2xpbmVhckdyYWRpZW50Pg0KCTxwYXRoIGZpbGw9InVybCgjU1ZHSURfMV8pIiBkPSJNMCwwaDEzMXYyMEgwVjB6Ii8+DQo8L2c+DQo8Zz4NCgk8ZyBlbmFibGUtYmFja2dyb3VuZD0ibmV3ICAgICI+DQoJCTx0ZXh0IHRyYW5zZm9ybT0ibWF0cml4KDEgMCAwIDEgMTcuNTM5NiAxNSkiIGZpbGw9IiMwMTAxMDEiIGZvbnQtZmFtaWx5PSInRGVqYVZ1U2FucyciIGZvbnQtc2l6ZT0iMTEiPlNvdXJjZTwvdGV4dD4NCgk8L2c+DQoJPHRleHQgdHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgMSAxNy41Mzk2IDE0KSIgZmlsbD0iI0ZGRkZGRiIgZm9udC1mYW1pbHk9IidEZWphVnVTYW5zJyIgZm9udC1zaXplPSIxMSI+U291cmNlPC90ZXh0Pg0KCTxnIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgICAgIj4NCgkJPHRleHQgdHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgMSA3Ny42NzQ4IDE1KSIgZmlsbD0iIzAxMDEwMSIgZm9udC1mYW1pbHk9IidEZWphVnVTYW5zJyIgZm9udC1zaXplPSIxMSI+UGFja2FnZTwvdGV4dD4NCgk8L2c+DQoJPHRleHQgdHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgMSA3Ny42NzQ4IDE0KSIgZmlsbD0iI0ZGRkZGRiIgZm9udC1mYW1pbHk9IidEZWphVnVTYW5zJyIgZm9udC1zaXplPSIxMSI+UGFja2FnZTwvdGV4dD4NCjwvZz4NCjwvc3ZnPg0K)](https://bioconductor.org/packages/release/bioc/src/contrib/DEsingle_1.0.3.tar.gz)
[![Windows Binary](data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxNi4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+DQo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IuWbvuWxgl8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgd2lkdGg9IjEzMXB4IiBoZWlnaHQ9IjIwcHgiIHZpZXdCb3g9IjAgMCAxMzEgMjAiIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDEzMSAyMCIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+DQo8ZGVmcz4NCgk8ZmlsdGVyIGlkPSJBZG9iZV9PcGFjaXR5TWFza0ZpbHRlciIgZmlsdGVyVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4PSIwIiB5PSIwIiB3aWR0aD0iMTMxIiBoZWlnaHQ9IjIwIj4NCgkJPGZlQ29sb3JNYXRyaXggIHR5cGU9Im1hdHJpeCIgdmFsdWVzPSIxIDAgMCAwIDAgIDAgMSAwIDAgMCAgMCAwIDEgMCAwICAwIDAgMCAxIDAiLz4NCgk8L2ZpbHRlcj4NCjwvZGVmcz4NCjxtYXNrIG1hc2tVbml0cz0idXNlclNwYWNlT25Vc2UiIHg9IjAiIHk9IjAiIHdpZHRoPSIxMzEiIGhlaWdodD0iMjAiIGlkPSJhIj4NCgk8cGF0aCBmaWxsPSIjRkZGRkZGIiBmaWx0ZXI9InVybCgjQWRvYmVfT3BhY2l0eU1hc2tGaWx0ZXIpIiBkPSJNMywwaDEyNWMxLjY1NiwwLDMsMS4zNDMsMywzdjE0YzAsMS42NTYtMS4zNDQsMy0zLDNIMw0KCQljLTEuNjU3LDAtMy0xLjM0NC0zLTNWM0MwLDEuMzQzLDEuMzQzLDAsMywweiIvPg0KPC9tYXNrPg0KPGcgbWFzaz0idXJsKCNhKSI+DQoJPHBhdGggZmlsbD0iIzU1NTU1NSIgZD0iTTAsMGg3MHYyMEgwVjB6Ii8+DQoJPHBhdGggZmlsbD0iIzE4ODFDMiIgZD0iTTcwLDBoNjF2MjBINzBWMHoiLz4NCgkNCgkJPGxpbmVhckdyYWRpZW50IGlkPSJTVkdJRF8xXyIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSItMjEzMS45NjE5IiB5MT0iNDEuMDUxOCIgeDI9Ii0yMTMxLjk2MTkiIHkyPSI0Mi4wNTE4IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEzMSAwIDAgMjAgMjc5MzUyLjUgLTgyMS4wMzEzKSI+DQoJCTxzdG9wICBvZmZzZXQ9IjAiIHN0eWxlPSJzdG9wLWNvbG9yOiNCQkJCQkI7c3RvcC1vcGFjaXR5OjAuMSIvPg0KCQk8c3RvcCAgb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjojMDAwMDAwO3N0b3Atb3BhY2l0eTowLjEiLz4NCgk8L2xpbmVhckdyYWRpZW50Pg0KCTxwYXRoIGZpbGw9InVybCgjU1ZHSURfMV8pIiBkPSJNMCwwaDEzMXYyMEgwVjB6Ii8+DQo8L2c+DQo8Zz4NCgk8ZyBlbmFibGUtYmFja2dyb3VuZD0ibmV3ICAgICI+DQoJCTx0ZXh0IHRyYW5zZm9ybT0ibWF0cml4KDEgMCAwIDEgMTEuNTM5NiAxNSkiIGZpbGw9IiMwMTAxMDEiIGZvbnQtZmFtaWx5PSInRGVqYVZ1U2FucyciIGZvbnQtc2l6ZT0iMTEiPldpbmRvd3M8L3RleHQ+DQoJPC9nPg0KCTx0ZXh0IHRyYW5zZm9ybT0ibWF0cml4KDEgMCAwIDEgMTEuNTM5NiAxNCkiIGZpbGw9IiNGRkZGRkYiIGZvbnQtZmFtaWx5PSInRGVqYVZ1U2FucyciIGZvbnQtc2l6ZT0iMTEiPldpbmRvd3M8L3RleHQ+DQoJPGcgZW5hYmxlLWJhY2tncm91bmQ9Im5ldyAgICAiPg0KCQk8dGV4dCB0cmFuc2Zvcm09Im1hdHJpeCgxIDAgMCAxIDgyLjY3NDggMTUpIiBmaWxsPSIjMDEwMTAxIiBmb250LWZhbWlseT0iJ0RlamFWdVNhbnMnIiBmb250LXNpemU9IjExIj5CaW5hcnk8L3RleHQ+DQoJPC9nPg0KCTx0ZXh0IHRyYW5zZm9ybT0ibWF0cml4KDEgMCAwIDEgODIuNjc0OCAxNCkiIGZpbGw9IiNGRkZGRkYiIGZvbnQtZmFtaWx5PSInRGVqYVZ1U2FucyciIGZvbnQtc2l6ZT0iMTEiPkJpbmFyeTwvdGV4dD4NCjwvZz4NCjwvc3ZnPg0K)](https://bioconductor.org/packages/release/bioc/bin/windows/contrib/3.5/DEsingle_1.0.3.zip)
[![Mac OS X 10.11](data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxNi4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+DQo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IuWbvuWxgl8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgd2lkdGg9IjEzMXB4IiBoZWlnaHQ9IjIwcHgiIHZpZXdCb3g9IjAgMCAxMzEgMjAiIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDEzMSAyMCIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+DQo8ZGVmcz4NCgk8ZmlsdGVyIGlkPSJBZG9iZV9PcGFjaXR5TWFza0ZpbHRlciIgZmlsdGVyVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4PSIwIiB5PSIwIiB3aWR0aD0iMTMxIiBoZWlnaHQ9IjIwIj4NCgkJPGZlQ29sb3JNYXRyaXggIHR5cGU9Im1hdHJpeCIgdmFsdWVzPSIxIDAgMCAwIDAgIDAgMSAwIDAgMCAgMCAwIDEgMCAwICAwIDAgMCAxIDAiLz4NCgk8L2ZpbHRlcj4NCjwvZGVmcz4NCjxtYXNrIG1hc2tVbml0cz0idXNlclNwYWNlT25Vc2UiIHg9IjAiIHk9IjAiIHdpZHRoPSIxMzEiIGhlaWdodD0iMjAiIGlkPSJhIj4NCgk8cGF0aCBmaWxsPSIjRkZGRkZGIiBmaWx0ZXI9InVybCgjQWRvYmVfT3BhY2l0eU1hc2tGaWx0ZXIpIiBkPSJNMywwaDEyNWMxLjY1NiwwLDMsMS4zNDMsMywzdjE0YzAsMS42NTYtMS4zNDQsMy0zLDNIMw0KCQljLTEuNjU3LDAtMy0xLjM0NC0zLTNWM0MwLDEuMzQzLDEuMzQzLDAsMywweiIvPg0KPC9tYXNrPg0KPGcgbWFzaz0idXJsKCNhKSI+DQoJPHBhdGggZmlsbD0iIzU1NTU1NSIgZD0iTTAsMGg3MHYyMEgwVjB6Ii8+DQoJPHBhdGggZmlsbD0iIzE4ODFDMiIgZD0iTTcwLDBoNjF2MjBINzBWMHoiLz4NCgkNCgkJPGxpbmVhckdyYWRpZW50IGlkPSJTVkdJRF8xXyIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSItMjEzMS45NjE5IiB5MT0iNDEuMDUxOCIgeDI9Ii0yMTMxLjk2MTkiIHkyPSI0Mi4wNTE4IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEzMSAwIDAgMjAgMjc5MzUyLjUgLTgyMS4wMzEzKSI+DQoJCTxzdG9wICBvZmZzZXQ9IjAiIHN0eWxlPSJzdG9wLWNvbG9yOiNCQkJCQkI7c3RvcC1vcGFjaXR5OjAuMSIvPg0KCQk8c3RvcCAgb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjojMDAwMDAwO3N0b3Atb3BhY2l0eTowLjEiLz4NCgk8L2xpbmVhckdyYWRpZW50Pg0KCTxwYXRoIGZpbGw9InVybCgjU1ZHSURfMV8pIiBkPSJNMCwwaDEzMXYyMEgwVjB6Ii8+DQo8L2c+DQo8Zz4NCgk8ZyBlbmFibGUtYmFja2dyb3VuZD0ibmV3ICAgICI+DQoJCTx0ZXh0IHRyYW5zZm9ybT0ibWF0cml4KDEgMCAwIDEgMTUuNTM5NiAxNSkiIGZpbGw9IiMwMTAxMDEiIGZvbnQtZmFtaWx5PSInRGVqYVZ1U2FucyciIGZvbnQtc2l6ZT0iMTEiPk1hYyBPUzwvdGV4dD4NCgk8L2c+DQoJPHRleHQgdHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgMSAxNS41Mzk2IDE0KSIgZmlsbD0iI0ZGRkZGRiIgZm9udC1mYW1pbHk9IidEZWphVnVTYW5zJyIgZm9udC1zaXplPSIxMSI+TWFjIE9TPC90ZXh0Pg0KCTxnIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgICAgIj4NCgkJPHRleHQgdHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgMSA3OS42NzQ4IDE1KSIgZmlsbD0iIzAxMDEwMSIgZm9udC1mYW1pbHk9IidEZWphVnVTYW5zJyIgZm9udC1zaXplPSIxMSI+WCAxMC4xMTwvdGV4dD4NCgk8L2c+DQoJPHRleHQgdHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgMSA3OS42NzQ4IDE0KSIgZmlsbD0iI0ZGRkZGRiIgZm9udC1mYW1pbHk9IidEZWphVnVTYW5zJyIgZm9udC1zaXplPSIxMSI+WCAxMC4xMTwvdGV4dD4NCjwvZz4NCjwvc3ZnPg0K)](https://bioconductor.org/packages/release/bioc/bin/macosx/el-capitan/contrib/3.5/DEsingle_1.0.3.tgz)

![Logo](https://github.com/miaozhun/DEsingle/blob/master/vignettes/DEsingle_LOGO.png?raw=true)

---

<br>

# Introduction

**`DEsingle`** is an R package for **differential expression (DE) analysis of single-cell RNA-seq (scRNA-seq) data**. It will detect differentially expressed genes between two groups of cells in a scRNA-seq raw read counts matrix.

**`DEsingle`** employs the Zero-Inflated Negative Binomial model for differential expression analysis. By estimating the proportion of real and dropout zeros, it not only detects DE genes **at higher accuracy** but also **subdivides three types of differential expression with different regulatory and functional mechanisms**.

For more information, please refer to the [manuscript](https://doi.org/10.1093/bioinformatics/bty332) by *Zhun Miao, Ke Deng, Xiaowo Wang and Xuegong Zhang*.

---

<br>

# Citation

If you use **`DEsingle`** in published research, please cite:

> Zhun Miao, Ke Deng, Xiaowo Wang, Xuegong Zhang (2018). DEsingle for detecting three types of differential expression in single-cell RNA-seq data. Bioinformatics, bty332. [10.1093/bioinformatics/bty332.](https://doi.org/10.1093/bioinformatics/bty332)

---

<br>

# Installation

To install **`DEsingle`** from [**Bioconductor**](http://bioconductor.org/packages/DEsingle/):

```R
source("https://bioconductor.org/biocLite.R")
biocLite("DEsingle")
```

To install the *developmental version* from [**GitHub**](https://github.com/miaozhun/DEsingle/):

```R
devtools::install_github("miaozhun/DEsingle", build_vignettes = TRUE)
```

To load the installed **`DEsingle`** in R:

```R
library(DEsingle)
```

---

<br>

# Input

**`DEsingle`** takes two inputs: `counts` and `group`.

The input `counts` is a scRNA-seq **raw read counts matrix** or a **`SingleCellExperiment`** object which contains the read counts matrix. The rows of the matrix are genes and columns are cells.

The other input `group` is a vector of factor which specifies the two groups in the matrix to be compared, corresponding to the columns in `counts`.

---

<br>

# Test data

Users can load the test data in **`DEsingle`** by

```R
library(DEsingle)
data(TestData)
```

The toy data `counts` in `TestData` is a scRNA-seq read counts matrix which has 200 genes (rows) and 150 cells (columns).

```R
dim(counts)
counts[1:6, 1:6]
```

The object `group` in `TestData` is a vector of factor which has two levels and equal length to the column number of `counts`.

```R
length(group)
summary(group)
```

---

<br>

# Usage

## Read counts matrix input

Here is an example to run **`DEsingle`** with read counts matrix input:

```R
# Load library and the test data for DEsingle
library(DEsingle)
data(TestData)

# Specifying the two groups to be compared
# The sample number in group 1 and group 2 is 50 and 100 respectively
group <- factor(c(rep(1,50), rep(2,100)))

# Detecting the DE genes
results <- DEsingle(counts = counts, group = group)

# Dividing the DE genes into 3 categories at threshold of FDR < 0.05
results.classified <- DEtype(results = results, threshold = 0.05)
```

<br>

## SingleCellExperiment input

The [`SingleCellExperiment`](http://bioconductor.org/packages/SingleCellExperiment/) class is a widely used S4 class for storing single-cell genomics data. **`DEsingle`** also could take the `SingleCellExperiment` data representation as input.

Here is an example to run **`DEsingle`** with `SingleCellExperiment` input:

```R
# Load library and the test data for DEsingle
library(DEsingle)
library(SingleCellExperiment)
data(TestData)

# Convert the test data in DEsingle to SingleCellExperiment data representation
sce <- SingleCellExperiment(assays = list(counts = as.matrix(counts)))

# Specifying the two groups to be compared
# The sample number in group 1 and group 2 is 50 and 100 respectively
group <- factor(c(rep(1,50), rep(2,100)))

# Detecting the DE genes with SingleCellExperiment input sce
results <- DEsingle(counts = sce, group = group)

# Dividing the DE genes into 3 categories at threshold of FDR < 0.05
results.classified <- DEtype(results = results, threshold = 0.05)
```

---

<br>

# Output

`DEtype` subdivides the DE genes found by `DEsingle` into 3 types: **`DEs`**, **`DEa`** and **`DEg`**.

* **`DEs`** refers to ***“different expression status”***. It is the type of genes that show significant difference in the proportion of real zeros in the two groups, but do not have significant difference in the other cells.

* **`DEa`** is for ***“differential expression abundance”***, which refers to genes that are significantly differentially expressed between the groups without significant difference in the proportion of real zeros.

* **`DEg`** or ***“general differential expression”*** refers to genes that have significant difference in both the proportions of real zeros and the expression abundances between the two groups.

The output of `DEtype` is a matrix containing the DE analysis results, whose rows are genes and columns contain the following items:

* `theta_1`, `theta_2`, `mu_1`, `mu_2`, `size_1`, `size_2`, `prob_1`, `prob_2`: MLE of the zero-inflated negative binomial distribution's parameters of group 1 and group 2.
* `total_mean_1`, `total_mean_2`: Mean of read counts of group 1 and group 2.
* `foldChange`: total_mean_1/total_mean_2.
* `norm_total_mean_1`, `norm_total_mean_2`: Mean of normalized read counts of group 1 and group 2.
* `norm_foldChange`: norm_total_mean_1/norm_total_mean_2.
* `chi2LR1`: Chi-square statistic for hypothesis testing of H0.
* `pvalue_LR2`: P value of hypothesis testing of H20 (Used to determine the type of a DE gene).
* `pvalue_LR3`: P value of hypothesis testing of H30 (Used to determine the type of a DE gene).
* `FDR_LR2`: Adjusted P value of pvalue_LR2 using Benjamini & Hochberg's method (Used to determine the type of a DE gene).
* `FDR_LR3`: Adjusted P value of pvalue_LR3 using Benjamini & Hochberg's method (Used to determine the type of a DE gene).
* `pvalue`: P value of hypothesis testing of H0 (Used to determine whether a gene is a DE gene).
* `pvalue.adj.FDR`: Adjusted P value of H0's pvalue using Benjamini & Hochberg's method (Used to determine whether a gene is a DE gene).
* `Remark`: Record of abnormal program information.
* `Type`: Types of DE genes. *DEs* represents differential expression status; *DEa* represents differential expression abundance; *DEg* represents general differential expression.
* `State`: State of DE genes, *up* represents up-regulated; *down* represents down-regulated.

To extract the significantly differentially expressed genes from the output of `DEtype` (**note that the same threshold of FDR should be used in this step as in `DEtype`**):

```R
# Extract DE genes at threshold of FDR < 0.05
results.sig <- results.classified[results.classified$pvalue.adj.FDR < 0.05, ]
```

To further extract the three types of DE genes separately:

```R
# Extract three types of DE genes separately
results.DEs <- results.sig[results.sig$Type == "DEs", ]
results.DEa <- results.sig[results.sig$Type == "DEa", ]
results.DEg <- results.sig[results.sig$Type == "DEg", ]
```

---

<br>

# Parallelization

**`DEsingle`** integrates parallel computing function with [`BiocParallel`](http://bioconductor.org/packages/BiocParallel/) package. Users could just set `parallel = TRUE` in function `DEsingle` to enable parallelization and leave the `BPPARAM` parameter alone.

```R
# Load library
library(DEsingle)

# Detecting the DE genes in parallelization
results <- DEsingle(counts = counts, group = group, parallel = TRUE)
```

Advanced users could use a `BiocParallelParam` object from package `BiocParallel` to fill in the `BPPARAM` parameter to specify the parallel back-end to be used and its configuration parameters.

<br>

## For Unix and Mac users

The best choice for Unix and Mac users is to use `MulticoreParam` to configure a multicore parallel back-end:

```R
# Load library
library(DEsingle)
library(BiocParallel)

# Set the parameters and register the back-end to be used
param <- MulticoreParam(workers = 18, progressbar = TRUE)
register(param)

# Detecting the DE genes in parallelization with 18 cores
results <- DEsingle(counts = counts, group = group, parallel = TRUE, BPPARAM = param)
```

<br>

## For Windows users

For Windows users, use `SnowParam` to configure a Snow back-end is a good choice:

```R
# Load library
library(DEsingle)
library(BiocParallel)

# Set the parameters and register the back-end to be used
param <- SnowParam(workers = 8, type = "SOCK", progressbar = TRUE)
register(param)

# Detecting the DE genes in parallelization with 8 cores
results <- DEsingle(counts = counts, group = group, parallel = TRUE, BPPARAM = param)
```

See the [*Reference Manual*](https://bioconductor.org/packages/release/bioc/manuals/BiocParallel/man/BiocParallel.pdf) of [`BiocParallel`](http://bioconductor.org/packages/BiocParallel/) package for more details of the `BiocParallelParam` class.

---

<br>

# Visualization of results

Users could use the `heatmap()` function in `stats` or `heatmap.2` function in `gplots` to plot the heatmap of the DE genes DEsingle found, as we did in Figure S3 of the [*manuscript*](https://doi.org/10.1093/bioinformatics/bty332).

---

<br>

# Interpretation of results

For the interpretation of results when **`DEsingle`** applied to real data, please refer to the *Three types of DE genes between E3 and E4 of human embryonic cells* part in the [*Supplementary Materials*](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/bty332/4983067#supplementary-data) of our [*manuscript*](https://doi.org/10.1093/bioinformatics/bty332).

---

<br>

# Help

Use `browseVignettes("DEsingle")` to see the vignettes of **`DEsingle`** in R after installation.

Use the following code in R to get access to the help documentation for **`DEsingle`**:

```R
# Documentation for DEsingle
?DEsingle
```

```R
# Documentation for DEtype
?DEtype
```

```R
# Documentation for TestData
?TestData
?counts
?group
```

You are also welcome to view and post *DEsingle* tagged questions on [Bioconductor Support Site of DEsingle](https://support.bioconductor.org/t/desingle/) or contact the author by email for help.

---

<br>

# Author

*Zhun Miao* < <miaoz13@mails.tsinghua.edu.cn> >

MOE Key Laboratory of Bioinformatics; Bioinformatics Division and Center for Synthetic & Systems Biology, TNLIST; Department of Automation, Tsinghua University, Beijing 100084, China.

---

