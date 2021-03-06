# Biostat1
For the [BASV94](https://r-training.pages.uni.lu/biostat1/) course 


### Installation

1. Setup the RStudio environment by cloning the repository

2. Activate [`renv`](https://rstudio.github.io/renv/articles/renv.html) by running `renv::activate()`. You might need to install `renv` by running `install.packages("renv
")`.
3. Run `renv::restore()` to install the package with the version. Say `y` to `Do you want to proceed? [y/N]:`



### Assignments

Complete the practicals and push to the repository. 

#### Practicals

The Rmd document are pre-filled, modify the header.


Currently it is the following:

~~~
---
title: "My answers"
author: "May name"
date: "2021-10-22"
---
~~~

Your tasks:

- Replace the title by either `dplyr` or `ggplot2` practical
- Replace the author name by yours
- Fix the date for today following the ISO8610 norm: `YYYY-MM-DD`
- Save the file
- Commit the changes
- Push to the github classroom

#### Answers

- Fill out the answer in the R chunks (default filled with a comment `# Write your answer here`)
- Knit the Rmd to check if everything works well
- If you use a new package (_i.e_ `palmerpenguis`), update the `renv.lock` with 
    + `renv::snapshot()`, new package are discovered, say `y` to `[yN]`
    + `Git` add the `renv.lock`, along with the completed Rmd
    + `Git` push
