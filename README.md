# Ethereum-Fraud-Detection-Model

## Project Objective

“ In 2016, false positives amounted to 19 percent of loss while actual fraud represented 7 percent of total cost of fraud.”

Our model aims to identify fraudulent transactions on the ethereum blockchain before they are written to the blockchain and reduce false positives
- Precision ( TP / TP + FP ) : of all predicted real frauds, how many are actual real frauds
  - Business focus
- Recall ( TP / TP + FN ) : of all real frauds, how many are we predicting correctly
  - User focus
- We will be focusing on precision to decrease false positives for our business, Ethereum


## Repository Structure

**Data** (transaction_dataset.csv)

- Contains the dataset used from source https://www.kaggle.com/vagifa/ethereum-frauddetection-dataset 

- Data is 1 csv file with 9841 rows and 51 columns (2.88 MB)

- This dataset is imbalanced (Fraud:18%; Non-fraud:82%)


**EDA and Modeling** (ETH Fraud Detection.ipynb , ETH Fraud Detection.html)

- Contains a notebook containing the data preprocessing, inital EDA, feature engineering, data balancing and modeling.


**Presentation** (Ethereum-Fraud-Detection-Presentation.pdf)

- Contains a pdf of the presentation of the project including project overview and conclusion and insights. 


## Models 

|    Model              |  Precision             |               
|:----------------------|:----------------------:|
|    Logistic Regression|         0.969         
|    Decision Tree      |         0.960      
|    Random Forest      |         0.995      
|    XGBoost      |         0.995      
|    SVM      |         0.977      



