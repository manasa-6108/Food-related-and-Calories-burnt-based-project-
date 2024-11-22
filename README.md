# Food related Calories burnt based project


EDA process to develop a machine learning model using Python which can predict the number of calories a person has burnt during a workout based on some biological measures.

## Importing Libraries and Dataset
Python libraries make it easy for us to handle the data and perform typical and complex tasks with a single line of code.

Pandas – This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.
Numpy – Numpy arrays are very fast and can perform large computations in a very short time.
Matplotlib/Seaborn – This library is used to draw visualizations.
Sklearn – This module contains multiple libraries are having pre-implemented functions to perform tasks from data preprocessing to model development and evaluation.
XGBoost – This contains the eXtreme Gradient Boosting machine learning algorithm which is one of the algorithms which helps us to achieve high accuracy on predictions.



![image](https://github.com/user-attachments/assets/0865de4a-47f8-4dee-a7f3-f4286238fd46)


For healthy intake food and excericse to live healthy span 

As expected higher is the duration of the workout higher will be the calories burnt. But except for that, we cannot observe any such relation between calories burnt and height or weight features.

Here we can observe some real-life observations:

The average height of the boys is higher than girls.
Also, the weight of the girls is lower than that of the boys.
For the same average duration of workout calories burnt by men is higher than that of women.

EDA prccess followed:
Data Cleaning
Data cleaning is always the first step in any data science project. Although the data here seems clean, some minor alterations are required.

Data Visualization and Analysis
Let's start the analysis by plotting the features with one another. This will not only provide us the distribution of features with one another but also give a quick quantitative feel of the data.

Model Training
Now we will separate the features and target variables and split them into training and testing data by using which we will select the model which is performing best on the validation data.

Out of all the above models, we have trained RandomForestRegressor and the XGB model’s performance is the same as their MAE for the validation data is same.
