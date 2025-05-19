# UberRides

![UberIMG](https://github.com/user-attachments/assets/faa1543d-6ee4-488c-abde-e05accc6446a)


### Objective
* Uber Rides Data Analysis
### Defining Data Analysis:
Data Analysis is the process of inspecting, cleaning, transforming, and modeling data to discover useful information, draw conclusions, and support decision-making.

<ins>The process of data analysis would include all these steps</ins>

* Defining the problem statement - Understand the goal, and what is needed to be done. In this case, our problem statement is - "The product is mostly sold out and list of customers who often visit the store." 
* Collection of data -  Not all the company's data is necessary, understand the relevant data according to the problem. Here the required columns are product ID, customer ID, and date visited.
* Preprocessing - Cleaning the data is mandatory to put it in a structured format before performing analysis. 
  - Removing outliers( noisy data).
  - Removing null or irrelevant values in the columns. (Change null values to mean value of that column.)
  - If there is any missing data, either ignore the tuple or fill it with a mean value of the column.

## Programming language ##
* Python 

## Libraries
The analysis will be done using the following libraries : 

* Pandas: This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.
* Numpy: Numpy arrays are very fast and can perform large computations in a very short time.
* Matplotlib / Seaborn: This library is used to draw visualizations.

## The Dataset
Path: https://www.kaggle.com/datasets/ruchikakumbhar/uber-dataset


### Columns:

- START_DATE : Date and time when the ride started
- END_DATE : Date and time when the ride stopped
- CATEGORY : business/personal
- START : start location
- STOP : destination
- MILES : distance covered
- PURPOSE : purpose of the ride

