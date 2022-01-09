
# Exploratory Data Analysis

Exploratory data analysis (EDA) is essential in any data science project. It cannot be a very long or concise process. Not too little. Not too much. It has to be correct/enough. Nevertheless, sometimes, without experience, it is not easy to know how long or how much time we need to spend on it. *"You need to build a sense of awareness for when your EDA process has gone long enough, and you have a good feel for the data"*.

# What does an EDA commonly include?



# What are the newest tools/libraries for EDA?

By far, **Numpy** and **Pandas** are the most used librearies to carry out an EDA. This powerfull libraries have very usefull methos and functions to make easy out life. 

### Pandas

**Methods**
  
  info(): returns a sumarize information about you dataframe. This sumarize report the number/names of the columns, the entrees you have, the data type of each column and how many non-null values you have in each column. Using this method you can realize which column has null values and it leads you to start asking yourself some questions.
  
  duplicated(): it returns a bolean series denoting duplicate rows. If you use duplicated().sum() and it returns 0, you are good to go!
  
  unique(): print the unique values of each column and you can understand the range of variation of each variable. Use it for discrete or categorical variables. Now, if you want to know how much of each unique value are, you have to use value_counts() method. It provedes you the unique values in that column that have the largest and smallest frequencies, and it is an amazing tool to look for outliers. 
  
  isnull().sum() return a list of each column in the dataframe with the amount of null values in each column. 
  
  replace(): with this method you can replace all entrees with an specific value or missing value for another value. It can be usefull to fill null values with zeros, for example. 
  
  **Filter rows in your dataframe**
  
  boxplot(): it creates a boxplot of all numerical columns. But it can be used to create a boxplot of a specific column too. How would you do it?
  
  corr(): it creates a correlation matrix for pairs of numeric columns. 
  
  [9 Simple Python Functions tha twill Speed up your Exploratory Data Analysis](https://medium.com/trymito/9-simple-python-functions-that-will-speed-up-your-exploratory-data-analysis-efaa6de9f8bb)
  
  
  
  
  
  
  
  
  
  
