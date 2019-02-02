Day 1
================

``` r
library(tidyverse)
```

    ## ── Attaching packages ───────────────────────────────────────────────────────────────────────────────────────────── tidyverse 1.2.1 ──

    ## ✔ ggplot2 3.0.0     ✔ purrr   0.2.5
    ## ✔ tibble  1.4.2     ✔ dplyr   0.7.6
    ## ✔ tidyr   0.8.1     ✔ stringr 1.3.1
    ## ✔ readr   1.1.1     ✔ forcats 0.3.0

    ## ── Conflicts ──────────────────────────────────────────────────────────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()

``` r
cancer <- read_csv("breast-cancer-wisconsin.csv", col_names = c("id","clump_Thickness","unif_Size","unif_Shape","marginal_Adhesion","epith_Size","bare_Nuclei","bland_Chromatin","normal_Nucleoli","mitoses","class"))
```

    ## Parsed with column specification:
    ## cols(
    ##   id = col_integer(),
    ##   clump_Thickness = col_integer(),
    ##   unif_Size = col_integer(),
    ##   unif_Shape = col_integer(),
    ##   marginal_Adhesion = col_integer(),
    ##   epith_Size = col_integer(),
    ##   bare_Nuclei = col_character(),
    ##   bland_Chromatin = col_integer(),
    ##   normal_Nucleoli = col_integer(),
    ##   mitoses = col_integer(),
    ##   class = col_integer()
    ## )
