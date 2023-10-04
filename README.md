# tsvio

tsvio is an R package of utilities for rapidly loading specified rows and/or columns of data
from large tab-separated value (tsv) files (large: e.g. 1 GB file of 10000 x 10000 matrix).

Basically, tsvio is an R wrapper to C code that creates an index file for the rows of the tsv file,
and uses that index file to collect rows and/or columns from the tsv file without reading the
whole file into memory.


## Installation from CRAN

```
install.packages("tsvio")
```

## Documentation

The following documentation is available:

- Main [CRAN repository page](https://cran.r-project.org/web/packages/tsvio/)
- Vignettes on [CRAN](https://cran.r-project.org/web/packages/tsvio/vignettes/tsvio.html)

