# Loan_Prediction_Machine_Learning

With the enhancement in the banking sector lots of people are applying for bank loans but the bank has its limited assets which it has to grant to limited people only, so finding out to whom the loan can be granted,
which will be a safer option for the bank is a typical process. We introduce an effective prediction technique that helps the banker to predict the credit risk for customers who have applied for loan. By predicting the loan
defaulters, the bank can reduce its Non-Performing Assets. This makes the study of this phenomenon very important.

## Problem Statement
There is a company named Dream Housing Finance that deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the
customer eligibility for loan. However doing this manually takes a lot of time. Hence it wants to automate the loan eligibility process (real time) based on customer information.So the final thing is to identify the factors/
customer segments that are eligible for taking loan. How will the company benefit if we give the customer segments is the immediate question that arises. The solution is . . . .Banks would give loans to only those
customers that are eligible so that they can be assured of getting the money back. Hence the more accurate we are in predicting the eligible customers the more beneficial it would be for the Dream Housing Finance
Company.

## Methodology 

Figure 3.1 describes the methodology. Firstly the information is collected from customers. We then clean the data where replace the missing numerical values with median and categorical values with their mode. In the third step, we train the model on the data set and in the following step, we base its accuracy on the test data set. Finally, evaluation will be done on AUC, Accuracy etc. The steps involved in Building the data model is depicted below:

<p align="center">
  <img src="https://user-images.githubusercontent.com/61707225/130238417-642b2d88-889b-475a-a51d-e76da52a5571.PNG" width="550"/>
</p>

## Exploratory Data Analysis
 - Univariate Analysis
 - Bivariate Analysis 
 - Data Cleaning
 - Dealing with Categorical Variables
 - Outlier Treatment
 
## Model Building 
- Logistic Regression
- K-nearest neighbours
- Naive Bayes
- Support Vector Machine Gaussian
- Decision Tree Classifier
- Random Forest Classifier
- Neural Network

## Results

<p align="center">
  <img src="(https://user-images.githubusercontent.com/61707225/130239775-4c744ef9-34ba-4f24-966a-402b0c71cc69.PNG" width="550"/>
</p>
Inferring from that, the Random Forest Classifier performs best on the dataset with an AUROC of 79%. After obtaining our best classifier, we implemented decision threshold tuning to obtain the optimal point in our ROC curve. We could achieve high recall for no-defaulters, but given the small dataset, we were able to
achieve moderate recall. Some simple classifiers like Naive Bayes Classifiers outperformed their more complex counterparts like SVM Gaussion or DTC. For Bank Loan Prediction, we need high precision combined with relatively high recall.
