Exercises: Visualising data (ggplot)
================

Ok, so now it is your turn!

*Remember, for the following exercises, inspiration for the code is available in the slides for this session*

-   Recall, that your basic script looks like this

``` r
# Clear workspace
# ------------------------------------------------------------------------------
rm(list=ls())

# Load libraries
# ------------------------------------------------------------------------------
library('tidyverse')

# Load data (session 2 - readr)
# ------------------------------------------------------------------------------

# Wrangle data (session 3 - dplyr)
# ------------------------------------------------------------------------------

# Visualise data (session 4 - ggplot)
# ------------------------------------------------------------------------------

# Write data (session 2 - readr)
# ------------------------------------------------------------------------------
```

-   Try to write in the code for your plots under the 'Visualise data' line

### Question 1

1.  Use the kommune data and the `count()` function to count the number of municipalities in the different regions

**Q1A** Which region has the fewest number of municipalities?

**Q1B** Make a barplot of the number of municipalities in each region

### Question 2

1.  Using the kommune data, make a scatter plot of `Pct_prv_sk_elev` as a function of `Videreg_udd`

**Q2** Are people with high education more likely to send their kids to private school?

### Question 3

1.  Using the kommune data, make a boxplot of the distribution of `Folkeskudg_elev` per `Region`

**Q3** Which `Region` has the highest median expense per public school pupil?

### Question 4

1.  Make a scatter plot of `Folkeskudg_elev` as a function of `Indt_indkskat` and add a linear model

**Q4** What is the trend? Are rich municipalities spending more or less per public school pupil, compared to municipalities with a lower average income?

### Question 5

1.  `R` has different data sets build in `diamonds`, `mtcars`, `iris`, `starwars` to name some

**Q5** Choose a data set and make a nice visualisation, see if you can ask a question from the data and find the answer using visualisation
