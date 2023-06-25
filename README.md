#                                           Binary_Multiple_Logistic_Regression_Model
Here I use a data set that I created by myself. In the data set we have four columns. In this project we build a Binary Multiple Logistic Regression  model and interpret its meaning.

## Introduction:
This projects gives a brief idea on Generalized linear models. More specifically it deals with those generalized linear models having dichotomous response variables and any type of predictor variables. Any type means the predictor variables can be continuous or categorical. 

## Data Selection:
Here I consider or rather I say construt a data set and name it as **Job_Satisfaction**. It is in the **.csv** format. It has **100 observations or rows** excluing column attributes and **4 variables or Columns**.


## Steps of Model Building:
Model building in data science is one of the most important job to do. Without building a model we can not solve the real life problems. To build a model we should follow three steps:

 1. First observe and understand the data set very keenly.
 2. Do data manipulation if requird
 3. Build the model as needed.

## Packages Used in This Project:
 Here in this project we use manily three packages. They are-
 1. **glmtoolbox**
 2. **tidyverse**
 3. **aod**

## Functions Used in This Project:
Here we give a brief discussion on the functions that we use to build this project along with their work in the project.

1. **install.packages()** - Used to install a package.
2. **linrary()** - Used to load the installed package.
3. **as.data.frame()** - Used to read a file in data frame format.
4. **read.csv()** - Used to read a csv file.
5. **head()** - Used to read first few rows of a data frame.
6. **str()** - Used to know structure of columns of data frame.
7. **summary()** - Used to get statistical summary of data.
8. **dim()** - Used to get the number of rows and columns.
9. **round()** - To round a number upto a specified decimal point.
10. **sapply()** - To do a fixed calculation on vectors.
11. **colnames()** - To get column names of the data frame.
12. **rename()** - To change the name of an existing column.
13. **sum()** - To count the number of a particular data. 
14. **is.na()** - To check for any non null values.
15. **table()** - To check frequency in different groups.
16. **factor()** - To change a column into categorical column.
17. **attach()** - To join the new columns with old data set.
18. **glm()** - To build a Generalized Linear Model.
19. **coef()** - To get the coefficients of the model estimators.
20. **hltest()** - To test the goodness of fit test. Also known   
      as Hosmer-Lomeshow test.
21. **confint()** - Used to find confidence interval.
22. **wald.test()** - To conduct the wald test.
23. **exp()** - to raise that value to the power of e.

### **Note:**
We write the inferences that we gained from the project by building the model in the Rmd and html document.
