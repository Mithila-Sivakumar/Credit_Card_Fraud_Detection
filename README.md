# Credit_Card_Fraud_Detection
The Credit Card Fraud Detection is an example of a binary classification problem. Here, we train the model using past transactions to find the fraudulent transactions on a future data set. The main objective of our project is to find the fraudulent transactions in a given synthetic transaction data set using 5 different data mining algorithms and compare the performance of each algorithm to determine the best fit

Project Report - Data_Mining_Project_Report.pdf
Pre-processing code - Pre_processing.ipynb
IVIS, Sampling, Data Mining Models - IVIS and Algorithms.ipynb

## Results

<b> A 3-D graph showing the clear partition of both classes (Red-Fraud, Blue- Not Fraud) when k=15 in IVIS: </b>
<img width="467" alt="Screen Shot 2023-04-18 at 3 37 02 PM" src="https://user-images.githubusercontent.com/127549357/232887040-8de3b725-d857-4477-8b7c-0afff7123e7c.png">


<b> Results of Data Mining Algorithms: </b>
<img width="327" alt="Screen Shot 2023-04-18 at 3 37 24 PM" src="https://user-images.githubusercontent.com/127549357/232886768-6a0323fb-9d7b-4fb4-9719-8f20aa252532.png">

## Summary

Our main methodology was to apply multiple pre-processing techniques, so that the features will be optimized in a way that will be well understood by the data mining algorithms. Since this a very large dataset, we gave importance to the type of sampling performed as well. Our main novelty in this project is the use of IVIS dimensionality reduction algorithm which no existing solutions have used. By using IVIS, we were able to acquire near perfect solution. We implemented 5 different algorithms on the final IVIS transformed dataset. From the results, it can be inferred that XGBoost performed the best of all algorithms with an ROC-AUC score of 97.4 percent.


