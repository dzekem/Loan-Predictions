# Loan-predictions using Linear Regression


Loan prediction is very important especially to the financial institution. This analysis helps the financial company know if there are higher chances of the applicant to be granted a loan or not, this is known from the past loan applicant's of the company..

# Data processing.

The dataset is in the form of a comma separated values (csv) which is directly imported and preprocessing starts.
First, the dataframe is checkecd for missing values and null values. After this, data analysis using plots is performed to see the different relationship between the features. Finally categorical variables are converted to numerical variables from which machine learning algorithms can then be performed on it.

# Implementation of Linear Regression

After converting the different features into numerical data, the dataframe is split into train and test where the model (Linear regression) is trained on this data and then compared with the the train output to see how accurate this model can be on such data. Accuracies > 80% are acceptable since the model doesn't overfit nor underfits the data. 
The test data too is tested on the model to make sure that the model accuracy doesn't decrease. Since it was maintained at the same level, the linear regression model is therefore a good option for this case.

# Importance of this Project

Insurrance companies have always been facing dificulties analyzing each loan applicant's documents to decide if they are qualified for a loan or not. With this system brough up, each applicant completes application for a loan and then the system which has already been built with the model to classify the different applicants and grade them under each group makes work more easier and less time consuming for a loan to be processed. 
At this point, the loan manager goes directly under each category and processes the applications with those under the "granted" category considered first.

