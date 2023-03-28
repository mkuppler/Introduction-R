# Introduction-R
The repository contains teaching materials for an introduction course to the statistical programming language R. The course is intended for students of Social Science with some basic knowledge of statistics. Prior experience with other statistical programming languages (e.g., STATA) is helpful but not required. The course is organized into four sessions and one homework:

- Session 1: Introduction to R and R Studio; creation and manipulation of objects (vectors, matrices, data frames, and lists)
- Session 2: Basic programming in R (if else structures, loops, writing own functions)
- Session 3: Importing and preparing survey data in R (with Tidyverse)
- Homework: Preparing the ALLBUS 2021
- Session 4: Data visualization (ggplot), descriptive statistics, regression models

The repository contains one folder for each session. The folders contain raw (.Rmd) and knitted (.html) RMarkdown notebooks that introduce and explain R code. A separate file contains the solutions for the training exercises. The folders for sessions 3 and 4 as well as the homework additionally contain subfolders for original data (odata), processed data (pdata), and output like tables and figures (output).

For sessions 3 and 4 as well as the homework, participants need access to the ALLBUS 2021 data set. The ALLBUS (Allgemeine Bevölkerungsumfrage der Sozialwissenschaften) is a yearly survey of the German population, comparable to the General Social Survey in the US. It started in 1980 and, since 1986, is conducted by GESIS. The ALLBUS 2021 data are available for free after registration under: https://search.gesis.org/research_data/ZA5280. Please place the downloaded and unzipped data set in the *odata* folder for sessions 3 and 4 as well as the homework.

The materials are suitable for self-study. Students should open the RMarkdown notebooks, type/copy the R code from the notebooks, and try to run the code in their own RStudio window.

Especially sessions 3 and 4 benefitted heavily from the *R for Data Science* book written by Hadley Wickham and Garrett Grolemund (available under https://r4ds.had.co.nz/).

For questions and feedback, please contact me under matthias.kuppler@uni-siegen.de. I am always grateful for reports on errors in the code.
