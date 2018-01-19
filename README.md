
<!-- README.md is generated from README.Rmd. Please edit that file -->
MSSLStyleGuide
==============

Research projects at the cPASS Machine-Learning for Social Science Lab (MSSL) are complex in terms of authors, methods, and data. MSSL has adopted a project management system based on Github, RStudio, and Latex that is:

-   efficient - everyone has access to every part of the project
-   organized - establishes a central repository for data, analysis, issues, and tasks
-   transparent - changes are tracked and previous iterations can be instantly recalled
-   replicable - when ready the repository can be made public and serve as the replication package

This Github repository titled MSSLStyleGuide documents this system as it develops and guides new users in setting up a work station, joining a project, and developing and documenting content.

Setup
-----

[01\_Workstation\_Setup](https://centerforpeaceandsecuritystudies.github.io/MSSLStyleGuide/01_Workstation_Setup.nb.html) - How to install and setup the software that you will use

[02\_Project\_Setup](https://centerforpeaceandsecuritystudies.github.io/MSSLStyleGuide/02_Project_Setup.nb.html) - How to get started on a specific project

[03\_Setup\_For\_Writing](https://centerforpeaceandsecuritystudies.github.io/MSSLStyleGuide/03_Setup_For_Writing.nb.html) - Alternative setup and workflow instructions for those who will only be contributing to papers and will not need R/RStudio.

Datawork
--------

### General Coding

Underscores "\_" not periods "."

### Data Storage

### Functions in R

#### Writing Functions

-   R functions go in their own individual .r file.
-   The name of the file should be the same as the name of the function
-   [Functions should have documentation using roxygen headers](https://centerforpeaceandsecuritystudies.github.io/MSSLStyleGuide/Function_Documentation.nb.html)

#### Calling Functions

-   [Calling functions from other packages](http://kbroman.org/pkg_primer/pages/depends.html)
-   As a lab, we'll be using the :: operator every single time we call a function from an external package, e.g. glue::glue, plyr::dplyr

### Packages

-   All calls to external packages should made on the Imports and Suggests lines in the DESCRIPTION file. Any calls to library() in the analysis should be commented out.
-   [Packrat](https://rstudio.github.io/packrat/)

### Analysis in R-Notebook

All analysis should be in an R-Notebook.

select File -&gt; New File -&gt; R Notebook

### R-Markdown

Each R-Markdown should be self-contained with unique outputs

Writing
-------

[TBD\_Syncing\_Edits](https://centerforpeaceandsecuritystudies.github.io/MSSLStyleGuide/TBD_Syncing_Edits.nb.html) - How to write and sync edits
