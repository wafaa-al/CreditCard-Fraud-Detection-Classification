# CreditCard Fraud Detection - Classification MVP


Wafaa Alharbi - Afnan Alserhani
</br>
ـــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــ


  


### Goal the project:
This project aim is to build machine learning models to classify fraudulent card transactions from a given card transactions data.
This system is useful for both people who use credit cards and banks to keep their customers safe.


### Data:
The dataset [CreditCardFraud] (https://www.kaggle.com/mlg-ulb/creditcardfraud)
 contains transactions made by credit cards in September 2013 by European cardholders.where we have 284,807 transactions with 29 features.
### Modeling workflow:
1- EDA, to find anomalies in the data such as duplicates, Nulls and outliers.
2- Feature engineering to enhance the model
3- Data split into training, validation and testing.
4- Dealing with imalance data by: SMOTE and ADASYN methods.
5- The following models are used:
5.1) Logstic regression (Baseline)
5.2) SVM
5.3) Random forest
5.4) XGboost
5.5) Decision trees

### Finding:
<img src="https://github.com/Wafaa-Alharbi/CreditCard-Fraud-Detection-Classification/blob/main/images/modelingf1.PNG" width="500"/> 

- As seen in above table the best model is : XGBClassifier.

<img src="https://github.com/Wafaa-Alharbi/CreditCard-Fraud-Detection-Classification/blob/main/images/heatmap-matrics.png" width="650"/> 

- The four models showen in above gragh is to distinguish between Froud and Valid transactions with the imbalanced classes.

### Future Work:
1- Try new models and choose the best F1 score.
</br>
2- use resampling method to deal with imbalance data.
</br>
3- The best model we will improve its performance
