# An Overview of the 2024 Mexican Presidential Election


Check the project requirements for what should go into this file.

- What is this GitHub repository is all about?

In this project we wanted to use our newly learned coding skills to look at the
2024 Mexican Presidential Election. We were curious as to how Claudia Sheinbaum 
won the election by an absolute landslide. We will review general election data,
issues that we considered very important based on research we had done and how 
they may have led to the results of the election. Most importantly we really 
wanted to try and explore these issues and if and how they may have impacted 
the Mexico states in who they elected.

- What software (with the version numbers) need to be installed to run the code
contained in this GitHub repository?

In order to truly access this data, Download:
- R (Mac or Windows, depending on computer): https://cran.r-project.org
- RStudio Desktop: https://posit.co/download/rstudio-desktop/  
(make sure you download the latest Rstudio version being 4.5 as of 2025)

- You should then clone or download this repository, then we recommend opening 
our eda's first then opening the index file. Open these up in Rstudio

- What steps need to be taken to run the code contained in this GitHub repository?

- Once Rstudio is downloaded and You have opened repository files be sure to install 
and download any and all packages needed to fully run our data


What would the output look like? 

Installing and making sure packages run (copy and paste into R chunk):

```{r}

install.packages("tidyverse")
install.packages("sf")
install.packages("RColorBrewer")
install.packages("viridis")
install.packages("stringi")
install.packages("janitor")
install.packages("forcats")


library(tidyverse)
library(sf)
library(RColorBrewer)
library(viridis)
library(stringi)
library(janitor)
library(forcats)

```


