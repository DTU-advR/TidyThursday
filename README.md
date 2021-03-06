CBio Thursday - Introducing Tidyverse in R
================

Before the Workshop
-------------------

Due to time constraints, it is *super important* that you make sure to go through the following *before* the workshop:

### Internet Connectivity

Please note, the following internet connectivity options sorted according to descending speed/stability:

-   DTU net if you are a student at DTU
-   [Eduroam](https://www.eduroam.org/) if you are a student at another University
-   DTU guest accounts (Arranged by CBIOvikings)
-   Your phone as an access point

### Workshop with no internet access

It is possible to attend the workshop with no internet connection, however then you *must* have succesfully installed [the latest version of R](https://mirrors.dotsrc.org/cran/) and also the [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download). Note you must install `R` first and then `RStudio`.

### Workshop with internet access

If you have internet access, then go to [RStudio Cloud](https://rstudio.cloud/) and create an account and start a new project.

### Installing Tidyverse

Once you have either `R/RStudio` running on your laptop or created an RStudio Cloud account, you can install [Tidyverse](https://www.tidyverse.org/) like so:

``` r
install.packages("tidyverse")
```

Congratulations! That's it! Now you're ready for the workshop - See you soon! Please be on time, we *will* start at 18.00

----- Do not proceed any further, we will go over the following at the workshop -----

At the Workshop
---------------

### Workshop Schedule

-   18.00 - 18.10 1. Introduction to the Tidyverse philosophy and the pipe ([`magrittr`](https://cran.r-project.org/web/packages/magrittr/README.html)) \[[Slides](http://htmlpreview.github.io/?https://github.com/leonjessen/TidyThursday/blob/master/01_introduction/lecture/introduction_presentation.html)\]

-   18.10 - 18.40 2. Data structures ([`tibble`](https://cran.r-project.org/web/packages/tibble/README.html)) and reading in data ([`readr`](https://cran.r-project.org/web/packages/readr/README.html)) (10 minutes lecture, 20 minutes exercises, 5 minutes wrap up) \[[Slides](http://htmlpreview.github.io/?https://github.com/leonjessen/TidyThursday/blob/master/02_readr/lecture/readr_presentation.html), [Exercises](https://github.com/leonjessen/TidyThursday/blob/master/02_readr/exercises/readr_exercises.md)\]

-   18.40 - 18.45 2. Data structures and reading in data - Exercises wrap up

-   18.45 - 19.00 Break

-   19.00 - 19.40 3. Wrangling data ([`dplyr`](https://cran.r-project.org/web/packages/dplyr/readme/README.html)) (10 minutes lecture, 30 minutes exercises, 5 minutes wrap up) \[[Slides](http://htmlpreview.github.io/?https://github.com/leonjessen/TidyThursday/blob/master/03_dplyr/lecture/dplyr_presentation.html), [Exercises](https://github.com/leonjessen/TidyThursday/blob/master/03_dplyr/exercises/dplyr_exercises.md)\]

-   19.40 - 19.45 3. Wrangling data - Exercises wrap up

-   19.45 - 20.00 Break

-   20.00 - 20.40 4. Visualising data ([`ggplot`](https://cran.r-project.org/web/packages/ggplot2/readme/README.html)) (10 minutes lecture, 30 minutes exercises, 5 minutes wrap up) \[[Slides](http://htmlpreview.github.io/?https://github.com/leonjessen/TidyThursday/blob/master/04_ggplot/lecture/ggplot_presentation.html), [Exercises](https://github.com/leonjessen/TidyThursday/blob/master/04_ggplot/exercises/ggplot_exercises.md)\]

-   20.40 - 20.45 4. Visualising data - Exercises wrap up

-   20.45 - 21.00 Q&A and workshop wrap up \[[Slides](http://htmlpreview.github.io/?https://github.com/leonjessen/TidyThursday/blob/master/05_wrapup/lecture/wrapup_presentation.html)\]

Resources
---------

### Web

-   [The R Project for Statistical Computing](https://www.r-project.org/)
-   [RStudio](https://www.rstudio.com/)
-   [RStudio Community](https://community.rstudio.com/)
-   [RStudio Cloud](https://rstudio.cloud/)

### Cheat Sheets

-   [RStudio IDE](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)
-   [Data Import with readr](https://github.com/rstudio/cheatsheets/raw/master/data-import.pdf)
-   [Data Transformation with dplyr](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf)
-   [Data Visualization with ggplot2](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf)

### Books

-   [R for Data Science by Garrett Grolemund and Hadley Wickham](https://r4ds.had.co.nz/)
-   [ModernDive - An Introduction to Statistical and Data Sciences via R](https://moderndive.com/)
