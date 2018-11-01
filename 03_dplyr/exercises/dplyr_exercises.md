Exercises: Wrangling data (dplyr)
================

Ok, so now it is your turn!

*Remember, for the following exercises, inspiration for the code is available in the slides for this session*

Since we now know how to load data and we are to work with how we manipulate (wrangle) data, now would be a good time for you to make your first script (small program).

-   In the upper right corner of RStudio, there is a small icon looking like a piece of paper with a green plus on it. Click it and choose the first option "R Script" (You can also use the short cut as described, on a mac it is command+shift+n). This will open a new empty text file in the RStudio editor, which we can put code into, save it and run it

-   A recipe for a script could look like the following. Copy/paste the code below into your new empty script file (Note, the '\#' means the line is ignored, so we use this for commenting our code)

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

-   Click the save icon and save your new script as "my\_script.R"

-   In RStudio in the icon line just above your script file, there is an icon again looking like a piece of paper, with a blue arrow and the word "Source". Click "Source", this will run each of the lines in the script (ignoring lines beginning with '\#'), so for now, it will simply clear the workspace of any variables and load the Tidyverse library every time you "Source" the script

### Question 1

1.  In the slides for this dplyr session, find where we load the kommune data directly from the web and write the command in the Console (Hint: All readr read-a-file-functions, start with 'read\_')
2.  In the slides for the readr session, find where we write a data set as a tab-separated-values file and save the kommune data to disk as 'kommune\_data.tsv', write the command in the Console (Hint: All readr write-a-file-functions, start with 'write\_'
3.  In your script under 'Load data' write the command for loading your data file 'kommune\_data.tsv' from disk and save it in a variable called `my_data` (Hint: This is completely analogue to reading a file from the web)
4.  Source the script and in the Console, simply write `my_data` and hit return

**Q1** How many rows and columns are in the kommune data set?

### Question 2

1.  Under 'Wrangle data' in your script, using the `mutate()` function write the command for calculating a new variable `inc_exp_ratio`, which is the ratio between `Indt_indkskat` and `Folkeskudg_elev`, i.e. `Indt_indkskat` divided by `Folkeskudg_elev` (Remember to save the result to your `my_data` variable)
2.  In the Concole, write `my_data` and hit return

**Q2** What is the value of this new variable for 'Koebenhavn'?

### Question 3

1.  Under 'Wrangle data' in your script, using the `filter()` function, write the command for identifying all the municipalities, where the value of your new variable is larger than 1
2.  Under 'Wrangle data' in your script, using the `filter()` function, write the command for identifying all the municipalities, where more than half have a long eduction and less than 1 in 5 pupils attend private scool

**Q3A** How many municipalities have a ratio larger than 1?

**Q3B** In how many municipalities do more than half have a long eduction and less than 1 in 5 pupils attend private scool?

### Question 4

1.  Under 'Wrangle data' in your script, using the `group_by()`, `summarise()` and `arrange` functions, write the command for identifying calculating the average % of students attending private school stratified on `Region` and sort them be falling values (largest first, smallest last)

**Q4** What is the order of Regions?
