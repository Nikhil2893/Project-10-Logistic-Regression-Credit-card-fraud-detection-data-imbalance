# Project-10-Logistic-Regression-Credit-card-fraud-detection-data-imbalance
Logistic Regression Credit card fraud detection data imbalance

About Dataset
Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

Update (03/05/2021)
A simulator for transaction data has been released as part of the practical handbook on Machine Learning for Credit Card Fraud Detection - https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html. We invite all practitioners interested in fraud detection datasets to also check out this data simulator, and the methodologies for credit card fraud detection presented in the book.

Acknowledgements
The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.
More details on current and past projects on related topics are available on https://www.researchgate.net/project/Fraud-detection-5 and the page of the DefeatFraud project

1. Importing Dependencies
2. Importing dataset and EDA

Dataset Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

![1](https://user-images.githubusercontent.com/114944969/229408980-d928b7bd-2097-4c42-84e2-4fb690fcd741.jpg)

![2](https://user-images.githubusercontent.com/114944969/229409236-7581e157-0b44-4b10-badd-5c18f703d2bf.jpg)

3. Splitting data into train and test

![3](https://user-images.githubusercontent.com/114944969/229409329-f699ee04-5f06-4b36-a126-f228bb7ca944.jpg)

4. Model Training with Logistic Regression

![4](https://user-images.githubusercontent.com/114944969/229409396-35f89573-30a5-4293-bda0-c60329f3444d.jpg)

5. Model Evaluation 

![5](https://user-images.githubusercontent.com/114944969/229409515-6904a486-19c6-4675-84d6-c929ec69dde8.jpg)

Model achieved accuracy of 93% on training data and 89% on test data


## Acknowledgements

I have followed the YouTube tutorial of "Siddardhan"

[Click for Video Link](https://www.youtube.com/watch?v=NCgjcHLFNDg&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6&index=10)

## Authors

- [Nikhil Wakode](https://github.com/Nikhil2893)

## Documentation

[Click the link to study Logistic Regression](https://www.geeksforgeeks.org/understanding-logistic-regression/)


## Installation

[No Installation is required to run the code as No UI app is created in this one. The predictive system can run on Google Colaboratory.
Please open the **"Project-10-Logistic-Regression-Credit-card-fraud-detection-data-imbalance.ipynb"** file with the help of Google Colaboratory]
(https://colab.research.google.com/)
    
## Lessons Learned

This is classification problem which could be solved by above mentioned steps in Introduction.

## 🚀 About Me
I'm a DATA SCIENCE enthusiast...

# Hi, I'm Nikhil! 👋

## 🛠 Skills
Machine Learning, Deep Learning - ANN,CNN,RNN, Computer Vision,NLP,Statistics,Strategic Planning, Urban Planning, Python, PostgreSQL, PowerBI, Tableau, Excel, GIS

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikhil-wakode
)

## Feedback

If you have any feedback, please reach out to us at 
ar.nikhilwakode@gmail.com

