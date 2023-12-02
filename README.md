# Marketing-Data-Analysis

1. First we know the objective of doing this project i.e. Infer relationship between sales and three media budgets: TV, Radio, and Newspaper.

1. Then, we import all the libraries that we use in this project.

2. Then, we load the given data.

3. After that we understand the data using following terms:-

    a) View the raw data with the help of .head() function which shows the first five columns of the data.
   
    b) Dimension of the data with the help of .shape function which gives the no. of columns and rows in the given dataset.
  
    c) Data types of the data with the help of .info() function which gives the whole information of the dataset.
  
    d) Null values of the data with the help of .isnull() function which shows the null value in the given dataset.
  
4. After that we do EDA(Exploratory Data Analysis) which consist the following terms:-

    a) Statistical data analysis with the help of .describe() function which gives count,mean,std,min etc.
 
    b) Relationship - Predictor and Response:-
    
      i)  Find the relationship between Sales and TV.
    
      ii) Find the relationship between Sales and Radio.
    
      iii) Find the relationship between Sales and Newspaper.
   
    c) Data Normalization. 

5. After that we do Data Modelling which consist following terms:-
  
    a) Linear Regression for Scaled Data using sklearn:- In this model we calculate the parameters i.e. intercepts and coefcients, calculate RSS,MSE,etc.
 
    b) Linear Regression for Unscaled Data using sklearn:- In this model we also calculate the parameters i.e. intercepts and coefcients, calculate RSS,MSE,R-sq etc. for unscaled data.
  
    c) Regression using Statsmodel:- In this model we can easily calculate all the values with the help of .summary() method.
  
    d) Single Linear Regression:- In this model we check the p-value and the relationship between sales and three media budgets one by one.
  
    e) Multiple Linear Regression:- In this model we also check the p-value and the relationship between sales and three media budgets at the same time.

6. At last we create the correlation matrix of the given dataset. 
