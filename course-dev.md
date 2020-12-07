# Notes about R Course

## Students

1st year biostat MS/MPH

- Few skills, inexperienced, base level of experience
- No programming skills

## Learning Goal 

- Rmarkdown/reproducibility
    - projects
- Loading data (`readr`/`readxl`/`haven`) *
- know basics of tidyverse, `dplyr`/`tidyr` *
    - `stringr` ()
    - `forcats` () *
- `ggplot2`/`plotly` (BERD flipbooks) *
    - `leaflet`
    - `gt`
- `broom`/stat component (needs to be extended)
- automation, functions, for loops/`purrr`
- `shiny` (stretch goal)

## Mini presentations

- Talk about a function (5 minutes)

## Final Project

- Low key 
- Short goals
- Diverse Topic

## Delivery

- RStudio.cloud projects
- Rstudio Desktop

Ready for R: https://ready4r.netlify.app/labbook/

## List of Packages

- `tidyverse`
- `tidymodels`/machine learning
- `shiny`

## Related Courses:

[Advanced R Kelly Bodwin/Hunter Glanz](https://cal-poly-advanced-r.github.io/STAT-431/)

[Data Carpentry for Biologists](https://datacarpentry.org/semester-biology/)

https://tladeras.shinyapps.io/learning_tidyselect/

https://github.com/laderast/ready_for_r_labs

https://coderefinery.org/lessons/

## To do

- Intro section (TL)
- Part 4 - JM expand
- Think of a name


## Outline of course

1. Part 1 (Intro to R/RStudio, Functions, Vectors, Data Types, R Markdown)
2. Part 2 (Loading Data (xls/haven)), data.frames, and ggplot2, projects
    a. load data from excel sheet and produce boxplot
    b. load data using haven and do something with it
3. Part 3 ggplot2, factors, boxplots, dplyr part 1, more flipbook stuff!
    a. load data, make boxplots, filter data
4. Part 4. dplyr: mutate, group_by/summarize, functions 
    
5. Part 5. More about manipulating factors and dates/doing things with multiple tables/for loops
6. Part 6. Functions/batch processing/purrr
    a. assignment
7. Part 7. Stats/formulas/broom
    a. assignment
8. Part 8. Tidymodels/machine learning basics/simulation (infer?/permutation)
    a. choose your adventure (limit choices) and explain
    b. Plot your results and report them
9. Part 9. Intro to Bioconductor
    a. DeSeq2 - 
10. Part 10. Wrap/up (shiny/interactive graphics) shiny/plotly, leaflet, tidytext 
11. Final Project? 
    a. TidyTuesday Dataset
    b. have to do EDA, must filter(), broom/tidymodels, report results

?RMarkdown/websites - https://rmd4sci.njtierney.com/

Learning aids - 


## Functions of the Week Assignment

Each of you will be responsible for a short write up about a `tidyverse` function. We'll feature these on the website's blog.

Why are we doing this? I believe that learning how to program is a lifelong journey and that you need to gain the skills how to teach yourself. 

Also, I believe that all of you have an important point of view and can help each other learn. Never forget that you can help each other.

## Report

Each write up should have the following:

1. A short explanation of what the function is for
2. An example using a dataset that shows what it's for. 
3. Bonus points: show as part of a `dplyr` pipeline or `ggplot2` statement.

Some good example datasets to use: `penguins`, `mtcars`, `gapminder`.

Sign up for a week to present your function. [Here]() is a template that you can use to present. 

You can pick any function you want, but this is a list of suggested functions that other people have found to be useful.

- `dplyr::relocate()`
- `dplyr::count() / add_count() / n()`
- `dplyr::distinct()`
- `dplyr::glimpse()`
- `dplyr::slice()`
- `ggplot2::geom_count()`
- `ggplot2::geom_hline()`
- `ggplot2::geom_violin()`
- `ggplot2::geom_jitter()`
- `ggplot2::cut_width()`
- `dplyr::lead() / lag()`
- `tidyr::fill()`
- `purrr::walk()`
- `tidyr::uncount()`
- `tidyr::separate()`/ `tidyr::separate_rows()`
- `forcats::fct_inorder()`
- `forcats::fct_infreq()`
- `forcats::fct_other()`
- `forcats::fct_lump()`
- `tidyr::na_if()`
- `tidyr::replace_na()`
- `lubridate::floor_date()`
- `dplyr::coalesce()`
- `tidyr::crossing()`
- `dplyr::pull()`
- `tibble::deframe()`
- `broom::add_predictions()`
- `pryr::partial()`

### Sources

https://github.com/robinsones/rstudio-conf-2018-talk/blob/master/Rstudio_conference_2018_presentation.pdf
https://dplyr.tidyverse.org/articles/window-functions.html
https://rstudio.com/resources/rstudioconf-2020/the-little-package-that-could-taking-visualizations-to-the-next-level-with-the-scales-package/
https://cmdlinetips.com/2019/12/10-tidyverse-tricks/


## Final Project

The final project should be focused on a dataset you're interested in. 

You should also set some goals for yourself before you start your project. It could be to learn a new geom, or a couple new functions, or to answer a particular question about the data.

Part of the grade will be a self evaluation based on the following criteria:

1. Did you meet or exceed your goals?
2. Did you learn something new?


## 

This course is meant to be a gentle introduction to data wrangling and visualization using the `tidyverse` in R. This course focuses on practical data science skills in R (loading data, data wrangling, visualization, automation, and running statistical models) that you'll use almost everyday in your work. It is meant for both beginners and students wanting to brush up in on their R skills.