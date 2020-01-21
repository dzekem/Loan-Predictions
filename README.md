# Loan-predictions using Gradient Boosting


Loan prediction is very important especially to the financial institution. This analysis helps the financial company know if there are higher chances of the applicant to be granted a loan or not, this is known from the information of the past loan applicant's of the company..

## Data processing.

The dataset is in the form of a comma separated values (csv) which is directly imported and preprocessing starts.
First, the dataframe is checkecd for missing values and null values. After this, data analysis using plots is performed to see the different relationship between the features. Finally categorical variables are converted to numerical variables from which machine learning algorithms can then be performed on it.

## Implementation of most suitable Machine Learning Model

After converting the different features into numerical data, the dataframe is split into train and test where suitable ML models are tested. Each model is trained on this data and then compared with the the train output to see how accurate this model can be on such data. Accuracies > 80% are acceptable but higher accuracy levels are more prefered which is the reason why the model with the highest accuracy score is always chosen. The test data too is tested on the model to make sure that the model accuracy doesn't decrease. 
SInce this is a classification problem with two categories the "Yes" and "No", some classification models were tested to see which one will best perform on this data without overfitting or underfitting the model.
The models that were considered were: K-Nearest Neighbours (KNN),Support Vector Machine (SVM) and Gradient Boosting. Training and testing these models, Gradient Boosting had the highest accuracy score with overfitting or underfitting the data. It was therefore the most suitable model for this case. 

## Importance of this Project

Insurrance companies have always been facing dificulties analyzing each loan applicant's documents to decide if they are qualified for a loan or not. With this system brough up, each applicant completes application for a loan and then the system which has already been built with the model to classify the different applicants and grade them under each group makes work more easier and less time consuming for a loan to be processed. 
At this point, the loan manager goes directly under each category and processes the applications with those under the "granted" category considered first.

