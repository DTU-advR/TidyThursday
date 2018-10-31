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

Congratulations! That's it! Now you're ready for the workshop - See you soon!

Tentative Schedule
------------------

-   18.00 - 18.10 1. Introduction to the Tidyverse philosophy and the pipe ([`magrittr`](https://cran.r-project.org/web/packages/magrittr/README.html)) \[[Slides](http://htmlpreview.github.io/?https://github.com/leonjessen/TidyThursday/blob/master/01_introduction/lecture/introduction_presentation.html)\]
-   18.10 - 18.45 2. Data structures ([`tibble`](https://cran.r-project.org/web/packages/tibble/README.html)) and reading in data ([`readr`](https://cran.r-project.org/web/packages/readr/README.html)) (10 minutes lecture, 25 minutes exercises) \[[Slides](), [Exercises]()\]
-   18.45 - 19.00 Break
-   19.00 - 19.45 3. Wrangling data ([`dplyr`](https://cran.r-project.org/web/packages/dplyr/readme/README.html)) (10 minutes lecture, 35 minutes exercises) \[[Slides](), [Exercises]()\]
-   19.45 - 20.00 Break
-   20.00 - 20.45 4. Visualising data ([`ggplot`](https://cran.r-project.org/web/packages/ggplot2/readme/README.html)) (10 minutes lecture, 35 minutes exercises) \[[Slides](), [Exercises]()\]
-   20.45 - 21.00 Q&A and wrap up
