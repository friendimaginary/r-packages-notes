## At Work

At work, this is what we load almost every time.

 * tidyverse
 * DBI
 * odbc
 * dbplyr
 * config
 * lubridate
 * magrittr
 * zoo
 * xts
 * dygraphs
 * readxl
 * openxlsx
 * imputeTS
 * eesinternal
 * boxr
 * googledrive
 * vroom

Some we use constantly, some are new to our workflow, and some are about to be phased out.

``` r
if ("pacman" %in% installed.packages() == FALSE) {
  install.packages("pacman")
}
pacman::p_load(
  "tidyverse",
  "DBI",
  "odbc",
  "dbplyr",
  "config",
  "lubridate",
  "magrittr",
  "zoo",
  "xts",
  "dygraphs",
  "readxl",
  "openxlsx",
  "imputeTS",
  "eesinternal",
  "boxr",
  "googledrive",
  "vroom"
 )
 ```
 
