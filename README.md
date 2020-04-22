# r_workshop_2020_04_24
Axel Nohturfft  
St. George's University of London  
24-April-2020  


## Topics covered  

1. Creating, reading and writing (saving) data frames  
2. Viewing, inspecting and summarising data frames  
3. The "tidy data" concept  
4. Editing and reshaping data frames  
5. Subsetting (filtering) and cleaning data  

## Preparation for the workshop  

### Expected background knowledge  

1. This will be a beginners/improvers workshop that builds on a [previous beginners workshop](https://github.com/nohturfft/r_workshop_2019_11_29) held in November last year. You are strongly encouraged to briefly review the material covered during the previous workshop.  
2. We will be working with scripts written in [Rmarkdown](https://rmarkdown.rstudio.com/); you might find it useful to familiarise yourself with this format if you haven't used it before. Consider downloading the [Rmarkdown cheat sheet](https://rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) as a handy reference.  


### Install R and RStudio  

If you haven't already done so, [install first R](https://www.r-project.org/), then [RStudio](https://rstudio.com/products/rstudio/download/) on your computer. That way you can try out the code we'll cover during the practice breaks. Of course, you may choose to just follow the presentation.  

### Install packages  

We will be using a number of different R packages.  
Please install these by running the following code from the command prompt (note: _**tidyverse includes 26 packages in total; so the installation may take a few minutes**_):  

```
install.packages("tidyverse")
install.packages("rmarkdown")
install.packages("knitr")
install.packages("DT")
```

Alternatively, you can install packages using the RStudio `Tools > Install Packages...` menu.  

### To create a copy of this repository in RStudio follow these steps:  

1. Start RStudio  
2. File menu > New project...  
3. Choose: Version Control > Git  
4. Paste the following address into the "Repository URL" field: https://github.com/nohturfft/r_workshop_2020_04_24  
5. Press tab key ("Project directory name" field will be filled automatically)  
6. Choose a desired folder in the "Create project as subdirectory of..." field  
7. Click the "Create project" button  
8. Open the first script ...