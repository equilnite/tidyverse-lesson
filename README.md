# Getting Around the tidyverse – Deconstructing Syntax and ggplot2

## Requirements

To run this app locally, R and RStudio need to be installed on your local machine

For reference, my R session info:

``` r
R version 3.6.3 (2020-02-29)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 18363)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252    LC_MONETARY=English_United States.1252
[4] LC_NUMERIC=C                           LC_TIME=English_United States.1252

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base

other attached packages:
 [1] forcats_0.5.0   stringr_1.4.0   dplyr_1.0.2     purrr_0.3.4     readr_1.4.0     tidyr_1.1.2     tibble_3.0.4
 [8] ggplot2_3.3.2   tidyverse_1.3.0 learnr_0.10.1

loaded via a namespace (and not attached):
 [1] tidyselect_1.1.0  xfun_0.18         haven_2.3.1       colorspace_1.4-1  vctrs_0.3.4       generics_0.0.2
 [7] htmltools_0.5.0   yaml_2.2.1        blob_1.2.1        rlang_0.4.8       later_1.1.0.1     pillar_1.4.6
[13] glue_1.4.2        withr_2.3.0       DBI_1.1.0         dbplyr_1.4.4      readxl_1.3.1      modelr_0.1.8
[19] lifecycle_0.2.0   cellranger_1.1.0  munsell_0.5.0     gtable_0.3.0      rvest_0.3.6       htmlwidgets_1.5.2
[25] evaluate_0.14     knitr_1.30        fastmap_1.0.1     httpuv_1.5.4      fansi_0.4.1       markdown_1.1
[31] broom_0.7.1       Rcpp_1.0.5        xtable_1.8-4      promises_1.1.1    backports_1.1.10  scales_1.1.1
[37] jsonlite_1.7.1    fs_1.5.0          mime_0.9          hms_0.5.3         digest_0.6.25     stringi_1.4.6
[43] shiny_1.5.0       rprojroot_1.3-2   grid_3.6.3        cli_2.1.0         tools_3.6.3       magrittr_1.5
[49] crayon_1.3.4      pkgconfig_2.0.3   ellipsis_0.3.1    xml2_1.3.2        reprex_0.3.0      lubridate_1.7.9
[55] assertthat_0.2.1  rmarkdown_2.4     httr_1.4.2        rstudioapi_0.11   R6_2.4.1          compiler_3.6.3
```

To properly run the RMarkdown file, make sure that the `tidyverse`, `learnr`, `shiny`, `rmarkdown`, and `knitr` packages are installed; these packages can be installed by running `install.packages(c('tidyverse', 'learnr', 'shiny', 'rmarkdown', 'knitr'))` in a R session.

## How to run:

### RStudio

If using R studio, simply click on the "Run Document" button on the top left of the coding pane.

### Terminal

If using the terminal, run `rmarkdown::run("lesson.Rmd")`.
