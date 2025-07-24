# KNN-Project
Two projects using KNN.

# iPhone Purchase Consumer Behavior
 Objective: Businesses want to predict whether a customer will purchase an iPhone given their gender, salary, and age. 

 Resource (dataset): iphone_purchase_records.csv

 Tools: Python, Tableau, Powerpoint, Excel

 Tableau Dashboard: https://public.tableau.com/app/profile/paloma.valdes/viz/iPhoneConsumerDemographics/Dashboard1

 Algorithms Used:
 - K-Nearest Neighbors (KNeighborsClassifier): Done possible through the Sci-Kit Learn Python library, the KNN algorithm classifies a new data point based on the majority class of its k-nearest neighbors.
 - Logistic Regression: A statistical method (commonly used in machine learning) that calculates the probability that a new data point belongs to a particular class.
 - Decision Tree: A supervised machine learning algorithim that operates on set "rules" to categorize data with different classes. 
 - Random Forest: An ensemble learning method that operates by using multiple decision trees during training. The output is the classification that was determined the most by the desicion trees. 

 Methodology:
 - Data preparation: The csv file has a column for gender, age, salary and whether the said person purchased the phone (1) or not (0). In my Jupyter Notebook, I analyzed the basic statistics (mean, median, and std. for age and salary) and the skewness of the data. This was to ensure that any outliers would not affect the model training and that, overall, the dataset had reasonable data. I checked if there was any missing information (there was not thankfully).

 - Model training: The four different models were trained one at a time. The processed data is fit to the model so that it is able to predict a given data point. Each model, I calculated the accuracy. 

Accuracy of the models:
 KNN: 87.5 %
 Logistic Regression: 83.75 %
 Decision Tree: 90.0 %
 Random Forest: 87.5 %

 Conclusion: The decision tree model proved to be the most accurate. This model would be extremely useful for market research for businesses who need to narrow down and cater to a more specific shopper demographic. This could also help with inventory management so that businesses know how much of a product they should anticipate to sell.  

