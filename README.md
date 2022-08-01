# Title: California Housing Price Prediction

1.	Background of Project
2.	Installation
3.	Data
4.	Implementation
5.	Results

### Background of Project:

This project examines the California Census Data published by the US Census Bureau.

The project aims to build a model of housing prices to predict median house values in California using the provided dataset. This model should learn from the data and be able to predict the median housing price in any district, given all the other metrics.

Districts or block groups are the smallest geographical units for which the US Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people). There are 20,640 districts in the project dataset.

### Installation
Python V-3.

**Python Libraries:**
-	Scikit Learn. 
-	Pandas. 
-	Numpy.
-	Seaborn
-	Matplotlib.

### Data
The data was gotten from the Simplilearn machine learning program and is one of the two capstone projects. More information [here](https://lms.simplilearn.com/courses/2789/Machine-Learning/syllabus)

### Implementation
Three classification models were run on the data, including Linear Regression, Decision Tree Regressor and Random Forest Regressor. The models were run on scaled training data  with a ratio of 70:30 and performance was reviewed using the accuracy score metric.The model with the lowest root mean squared error (RMSE) was used to predict output for test dataset using the fitted model.

### Results
Results are presented in the notebook
