# StudentDemo
A demo repository of using GitHub/Rstudio workflow

## Get started

1. Fork this repository to your own GitHub account
2. Install RStudio
3. Copy the link to the repository in your account, should be something like https://github.com/your_username/StudentDemo
4. Create a new project in Rstudio, select "From version control", enter the URL and follow the instructions.
5. Feel free to play around with the examples in this repository to learn Git, Rmarkdown and the Rstudio integration.
  
Tip! Files that are markdownfiles can be edited and commited right here in GitHub! Which comes in handy for meeting notes and README documents.

## Useful links

GitHub introduction:

Rstudio introduction: 

## Example of meeting notes

Markdown examples of meeting-notes be found in the meetings folder.
  
## Rmarkdown example

  Can be found in the `docs` folder.
  
  ## Using packages and noacsr
  
  R uses alot of packages that contain code and functions, these may be for data handling, integrating with services or creating plots and graphs. The most common that you will likely use is [tidyverse](https://www.tidyverse.org)(Which is a collection of packages), [devtools](https://devtools.r-lib.org) and [ggplot2](http://ggplot2.tidyverse.org).   
  Within the lab we have an R package called [noacsr](https://github.com/martingerdin/noacsr) that is under development. This package contains a function to create a new project that creates the files that you will need. To install these packages in R do:    
  
  `install.packages(c("devtools", "tidyverse", "ggplot2")`
  `library(devtools)`
  
  To install the noacsr package, you need to install it from GitHub like this:   
  
  ```{r}
devtools::install_github("martingerdin/noacsr")
```

And start using with:

```{r}
library(noacsr)
```
  
  
