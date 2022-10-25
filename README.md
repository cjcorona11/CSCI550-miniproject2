# CSCI550-miniproject2

Mini Project 2: 

In this assignment, we will use a housing dataset to estimate the price of a house based on information about the house, such as overall property quality, area of living space, garage area, size of the basement, and lot size.
You can access the dataset .csv file and its metadata here.
The dataset contains information from the Ames Assessor's Office used in computing assessed values for individual residential properties sold in Ames, IA, from 2006 to 2010.
This dataset has 2930 rows and 82 variables, including 23 nominal, 23 ordinals, 14 discrete, and 20 continuous variables (and two additional observation identifiers).
The objectives of this assignment are to learn and practice:
1-	Data cleaning (if necessary) and exploratory data analysis
2-	Feature selection methods
3-	Different linear regression methods, and non-linear regression methods
4-	Regularization methods
5-	Cross-validation 

Deliverable:
A markdown or Jupyter notebook report containing:

-   A Summary: 
A concise summary of the assigned task, your analysis, results, recommendations, and potential future work. Your summary should be concise, easy to understand by a non-technical audience, and recommendation oriented. 

-  A data preprocessing and exploratory analysis:
 For example, drop any uninformative predictors, take care of missing values or outliers (if any), and do some insightful preliminary analysis. It is expected that any visualization comes with a proper interpretation. You can even discuss any hypothesis that you developed about the importance of predictors and so on.

- Model development and performance evaluation:
These are a couple of expectations for this assignment but feel free to try other methods and approaches to improve the accuracy.
-	Use a subset selection approach to select a model with the highest prediction power.
-	Use l1 and l2 regularization approaches to develop a model with the highest prediction power.
-	Use PCA to select the best model.
-	Use “year built” and build a simple linear model, polynomial, smooth spline.
-	Compare all prediction errors and make an insightful conclusion
Note: for each step, use the 10-fold cross-validation error to select the tuning parameter 
