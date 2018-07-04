**Materials have not been updated yet for Summer 2018 - in progress.**

# R Visualization

This workshop focuses on `ggplot2` for making plots in R.  The workshop also briefly covers `plotly`.  

This workshop also makes use of other `tidyverse` packages for data manipulation and transformation.

# Software and Files

For this workshop, you'll need to install some R packages and download the workshop files from this repository.

Keynote and Powerpoint versions of the slides will be included when you download the repository (below).  If you don't have either of these programs, try opening the slides with [Google Slides](https://docs.google.com/presentation/u/0/) or [PowerPoint Online](https://support.office.com/en-us/article/view-a-presentation-without-powerpoint-2f1077ab-9a4e-41ba-9f75-d55bd9b231a6).

## Option 1: On your laptop 

### R and RStudio

This workshop assumes you have recent versions of R and RStudio - R 3.4 or 3.5 and RStudio 1.1.

You'll also need the following packages and their dependencies installed and up to date:

* tidyverse

```r
install.packages(c("tidyverse"), 
                 repos="http://cran.rstudio.com")
```


### Workshop Materials

To download workshop materials (final versions will be available 2-3 days before the workshop), click on the green Clone or Download button, then download the repository as a ZIP file.  

![github download](images/githubdownload.png)

Find the downloaded .zip file on your computer, likely in your Downloads folder.  Unzip it - usually by double-clicking.  This will create a directory called r\_ggplot2\_june2018.  Move this somewhere on your computer where you'll be able to find it, like your Documents folder.  

Double click on the .Rproj folder in the folder to launch the project in RStudio.  Alternatively, open RStudio, then go to File :arrow_right: Open Project and find the .Rproj file in the r\_ggplot2\_june2018 directory to open.

Alternatively, if you're familiar with git, you can create a new RStudio project directly from this repository (again, once the materials are posted).


## Option 2: RStudio Cloud

[RStudio Cloud](https://rstudio.cloud) is a way to run RStudio in your web browser.  Set up an account.  In Your Workspace, create a New Project, selecting New Project from a Git Repository.  Provide the address of this repository: https://github.com/nuitrcs/r_ggplot2_june2018.  This will copy all of the files from this repository into your new project.  

*You should wait until 2-3 days before the workshop to do this, to ensure you have the most current version of the workshop files.**

You will also need to install packages in this project space:

* tidyverse

With the project open (opening the project will open RStudio in your web browser), install these with the R command

```r
install.packages(c("tidyverse"), 
                 repos="http://cran.rstudio.com")
```

or use the buttons in the Packages window in the bottom right of RStudio to install them.



# Resources

See additional resources and links to some visualization examples in the [main R workshop repository](https://github.com/nuitrcs/rworkshops).

## Reference

[`ggplot2` Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf): you'll want to have this for reference

[R Graph Gallery](http://www.r-graph-gallery.com/portfolio/ggplot2-package/) for `ggplot2`

[R Graphics Cookbook](https://ase.tufts.edu/bugs/guide/assets/R%20Graphics%20Cookbook.pdf)

[Cookbook for R](http://www.cookbook-r.com/Graphs/)

[`ggplot2` Data Visualization Vocabulary](https://medium.com/@kierisi/fc8fa4d20d2d) from Jesse Maegan: confused by unfamiliar terms in the `ggplot2` help and functions?  You can find explanations of many of them here.

[`ggplot2` Extensions](https://blog.modeanalytics.com/r-ggplot-extension-packages/): a list of packages that build on `ggplot2` to add specific plots or functionality

## Tutorials

[`ggplot2` Tutorial](http://seananderson.ca/ggplot2-FISH554/) from Sean Anderson, University of Washington

[`ggplot2` Tutorial](http://tutorials.iq.harvard.edu/R/Rgraphics/Rgraphics.html) From the Harvard IQSS Data Science Services group.

[Getting started with data visualization in R using `ggplot2`](http://www.storybench.org/getting-started-data-visualization-r-using-ggplot2) from Martin Frigaard at Storybench

[`ggplot2` Tutorial](http://r-statistics.co/ggplot2-Tutorial-With-R.html) from Selva Prabhakaran with examples of many different kinds of plots

[An introduction to ggplot2](https://rawgit.com/eco-data-science/VisualizingData/master/ggplot2_intro.html) by Melanie Frazier, shows lots of color/style options along with a good general overview of ggplot

Software Carpentry: [R for Reproducible Scientific Analysis](http://swcarpentry.github.io/r-novice-gapminder/08-plot-ggplot2/): course material for introductory R workshop, includes a section on `ggplot2`

[Swirl](http://swirlstats.com/): Interactive tutorials that you run in R.  The Exploratory Data Analysis course includes sections on `ggplot2`.


## Books

[`ggplot2` Elegant Graphics for Data Analysis](http://ggplot2.org/book/) by Hadley Wickam, who wrote the package.  The book can also be downloaded as a pdf by going through the Library.  The book's code is [here](https://github.com/hadley/ggplot2-book).

[R for Data Science](http://r4ds.had.co.nz/): free online book using the `tidyverse` of packages, has a chapter on [data visualization](http://r4ds.had.co.nz/data-visualisation.html).  It includes a chapter on [Graphics for communication](http://r4ds.had.co.nz/graphics-for-communication.html) which doesn't teach `ggplot2` so much as give you good principles of making charts with it.

[Data Visualization for Social Science](http://socviz.co/): by Kieran Healy, an online book that uses `ggplot2`

## Plotly

[Plotly Tutorial](https://www.datacamp.com/community/blog/a-free-interactive-plotly-r-tutorial)

[Plotly for R](https://cpsievert.github.io/plotly_book/index.html) by Carson Sievert

## Base R Graphics

A comparison on Base graphics and `ggplot2` from [Flowing Data](http://flowingdata.com/2016/03/22/comparing-ggplot2-and-r-base-graphics/), which is a great site in general for R graphics, but he doesn't use `ggplot2`.


## More Help

[Stack Overflow](http://stackoverflow.com/questions/tagged/ggplot): great for searching for issues; most questions you have will have already been asked by someone else; be aware of the date of answers, as sometimes an answer may be a little out of date.

## Colors, Styles, and Formats

[colorblindr](https://www.rdocumentation.org/packages/colorblindr): package to help you check what your plots might look like to someone who is colorblind


