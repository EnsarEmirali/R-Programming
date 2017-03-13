## R-Programming
This is notes from coursera lecture: The Data Scientist’s Toolbox. Therefore, it is so personal! Use it for only education.

###CLI Commands
* cd: takes as an argument the directory you want to visit (cd Music/Debussy) OR with no argument takes you to your home directory (cd)
* cd..: allows you to change directory to one level above your current directory

###R Commands
R has five atomic classes of objects: character, numeric, integer, complex, logical.
Main basic object of R is vector, objects of same class. List is a kind of vector which can contain different classes.
If you explicitly want an integer, need to specify L suffix (e.g. 1L).
Inf represents infinity (e.g. 1/0=Inf).
NaN represents an undefined value (e.g. 0/0=NaN).


* [function]: information about the function
* [?function]: help information about the function
* args(myfunction): arguments of the myfunction function
* available.packages(): obtain information about available packages on CRAN
* install.packages("slidify"): install slidify package
* library(slidify): to load slidify package into R
* search(): to list functions exported by package which one is loaded
* getwd(): to get current working directory
* read.csv("mydata.csv"): to load mydata csv file
* dir(): to list files on working directory
* setwd("~/R-Programming"): to change working directory as R-Programming file
* source("myfunction.R"): to laod myfunction function saved as myfunction.R
* ls(): to list objects on current working environment
* ##: everything to right this symbol is comment
* vector('numeric', lenght=10): to create an empty vector
* attributes(x): to access attributes of an object
* c(T,F): to create vectors of bjects
* as.numeric(x): to coerce the object to numeric class/ as.*: to coerce object from one class to another



