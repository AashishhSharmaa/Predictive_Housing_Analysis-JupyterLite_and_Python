# Predictive Housing Analysis in King County, USA

In this JupyterLite-based Python project, we delved into the analysis of housing data from King County, including Seattle. Employing techniques such as data wrangling, exploratory analysis, and various regression models, our goal was to predict residential real estate prices. The project showcased a comprehensive approach to data analysis, modeling, and evaluation, providing valuable insights for informed decision-making in real estate investments.

## Problem Statement

As a Data Analyst at a Real Estate Investment Trust, the objective is to initiate investments in Residential real estate. The task involves determining house market prices based on features such as square footage, number of bedrooms, and floors. The analysis and prediction will be conducted through ten questions in a provided template notebook, with hints for guidance. The dataset comprises house sale prices in King County, including Seattle, from May 2014 to May 2015. Utilizing JupyterLab in the Cloud within the Skills Network Labs environment ensures efficient project execution.

## Solution Summarry

**Module 1: Importing Data sets**

In the initial stages of the project, we began by importing the dataset and displaying the first 5 columns of the dataframe using the `head` method. 

![Module 1](https://github.com/AashishhSharmaa/Predictive_Housing_Analysis-JupyterLite_and_Python/assets/152653168/9d0ac3b4-2301-4719-8c83-5f3a5bd95c3e)

Additionally, we employed the `dtypes` function to unveil the data types of each column, laying the foundation for a comprehensive understanding of the dataset's structure.

**Question 1:**
![QUESTION 1 ](https://github.com/AashishhSharmaa/Predictive_Housing_Analysis-JupyterLite_and_Python/assets/152653168/9c0dbe76-82f8-49fa-90a1-512238007435)

**Module 2: Data Wrangling**

**Question 2:**
Dropped the columns "id" and "Unnamed: 0" from axis 1 using the `drop()` method.

![QUESTION 2 ](https://github.com/AashishhSharmaa/Predictive_Housing_Analysis-JupyterLite_and_Python/assets/152653168/ff52f0df-3a3c-44f7-b424-e8699806fda7)

**Question 3:**
Used the `describe()` method to obtain a statistical summary of the data.

![QUESTION 3 ](https://github.com/AashishhSharmaa/Predictive_Housing_Analysis-JupyterLite_and_Python/assets/152653168/1f3952fe-b60f-49f8-85c1-23b6b18077ed)

**Module 3: Exploratory Data Analysis**

**Question 4:**
Used the `value_counts` method to count the number of houses with unique floor values.
![QUESTION 4 ](https://github.com/AashishhSharmaa/Predictive_Housing_Analysis-JupyterLite_and_Python/assets/152653168/d6d77f09-9a76-4619-8f08-b31da478a3e3)
Created a boxplot using the `boxplot` function in the seaborn library to compare house prices with and without a waterfront view.




