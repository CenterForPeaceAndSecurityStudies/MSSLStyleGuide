
<!-- README.md is generated from README.Rmd. Please edit that file -->
MSSLStyleGuide
==============

Research projects at the cPASS Machine-Learning for Social Science Lab (MSSL) are complex in terms of authors, methods, and data. To efficiently and transparently manage these projects, MSSL has established a project system based on Github, RStudio, and Latex. This Github repository titled MSSLStyleGuide documents this system as it develops and guides new users in setting up a work station, joining a project, and developing and documenting content.

R Projects
----------

### General

Underscores "\_" not periods "."

### Packages

-   All calls to external packages should made on the Imports and Suggests lines in the DESCRIPTION file. Any calls to library() in the analysis should be commented out.
-   [Packrat](https://rstudio.github.io/packrat/)

### Functions

#### Writing Functions

-   R functions go in their own individual .r file.
-   The name of the file should be the same as the name of the function
-   [Functions should have documentation using roxygen headers](https://rexdouglass.github.io/MSSLStyleGuide/Function_Documentation.nb.html)

#### Calling Functions

-   [Calling functions from other packages](http://kbroman.org/pkg_primer/pages/depends.html)
-   As a lab, we'll be using the :: operator every single time we call a function from an external package, e.g. glue::glue, plyr::dplyr

### R-Notebooks

All analysis should be in an R-Notebook.

select File -&gt; New File -&gt; R Notebook

### R-Markdown

Each R-Markdown should be self-contained with unique outputs
