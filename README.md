## R-Programming
These notes are from coursera lectures: Data Science. Therefore, it is so personal! Use it for only education.

###CLI Commands
* cd: takes as an argument the directory you want to visit (cd Music/Debussy) OR with no argument takes you to your home directory (cd)
* cd..: allows you to change directory to one level above your current directory

###R Commands
R has five atomic classes of objects: character, numeric, integer, complex, logical.
* Main basic object of R is vector, objects of same class. 
* List is a kind of vector which can contain different classes.
* Matrices are vectors with a dimension attribute (e.g. matrix(nrow=r, ncol=c)). Entries can be thought of starting in the upper left corner and running down the columns (e.g. m<-1:10; dim(m)<-c(2,5)).
* Factors are used to represent categorical data like an integer vector where each integer has a label (e.g. factor(c(T,F,T,F))).
* Data frames are used to store tabular data. They are represented same lenght elements of the list and columns have names (e.g. data.frame(foo=1:4,bar=c(T,F,T,F)).


If you explicitly want an integer, need to specify L suffix (e.g. 1L).
Inf represents infinity (e.g. 1/0=Inf).
When coercion does not work, you get NA values. NA values have a class, so there are integer NA, character NA, etc.
NaN represents an undefined value (e.g. 0/0=NaN). NaN is a NA but converse is not true.

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
* as.numeric(x): to coerce the object to numeric class
* cbind(a,b): to create column binding matrix
* rbind(x,y): to create row binding matrix
* table(x): to represent count of labels
* unclass(x): to convert factors into integer vector by coding each label
* is.na(): to check whether the object is NA
* is.nan(): to check whether the object is NaN
* row.names(dFrame): to list row name of data frame
* data.matrix(dFrame): to convert data frame into a matrix
* nrow(dFrame): to count rows of data frame
* ncol(dFrame): to count columns of data frame
* names(x): to give names to rows of vector x
* dimnames(x): to give names to rows of matrix x
* 
