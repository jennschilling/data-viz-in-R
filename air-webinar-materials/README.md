**Data Visualization in R - Webinar Materials**

This directory contains the slides, data, and code for webinar: Data Visualization in R, presented for the Association for Institutional Research by Jenn Schilling on April 12 & 13 2021.  


**Webinar Details** 

This two-part webinar series will introduce individuals with a basic understanding of R and data manipulation in R to data visualization in R. Through guided exercises and presentations, participants will learn how to build and polish data visualizations using the grammar of graphics in R. The series will also include tips on data visualization best practices, creating reproducible code, and outputting data visualizations in R. This series is ideal for higher education professionals who have some experience in R and want to add data visualization to their R skills.  

As a result of this webinar, participants will be able to: 

- Explain how the grammar of graphics works in R. 
- Create three different plots in R. 
- Add titles and labels to a plot in R. 
- Change the formatting of a plot in R. 


**Folder Structure**

- code: Contains an R Markdown document that loads the data, processes the data, and creates the plots shared in the webinar. The setup and data preparation code chunks must be run prior to running any of the code chunks related to plotting.

- data: Contains the CSV data files and data dictionaries downloaded from the IPEDS website for 2017, 2018, and 2019. These data files are used in the R Markdown document as the data source for the plots.

- plots: This folder is currently empty, but it is folder in which a plot is saved at the end of the R Markdown document. After that portion of the code is run, this folder will contain the plot image file. 


**How to Use These Files**

1. Save all three folders in the same directory on your computer.

2. Open the R Markdown document in the *code* folder in RStudio.

3. Run the setup, get-inst-ids, get-adm-data, get-enrlmnt-data, and get-compl-data code chunks to load the libraries, read the data, and process the data. 

Note: The two libraries used are `here` and `tidyverse`. If you do not have these packages installed, be sure to complete the installation prior to running the code by running `install.packages(c('here', 'tidyverse'))` in the Console of RStudio. 

4. Run any of the code chunks that create plots.

