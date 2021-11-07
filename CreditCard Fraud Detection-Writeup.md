# CreditCard Fraud Detection Classification


Wafaa Alharbi - Afnan Alserhani
</br>
ـــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــ


##### Abstract:
This project aim is to build machine learning models to classify fraudulent card transactions from a given card transactions data.
This system is useful for both people who use credit cards and banks to keep their customers safe.

##### Design:
In order to determine the types of transction statue, data was downloaded from Kaggele. Then, multiple models were implemented to get the best one to make a clear classification.

### Data:
The dataset [CreditCardFraud] (https://www.kaggle.com/mlg-ulb/creditcardfraud)
 contains transactions made by credit cards in September 2013 by European cardholders.where we have 284,807 transactions with 29 features.
 
### Algorithms:
- Exploratory Data Analysis was done to the dataset.
- Building multple models and finding out the well-suited one for this specific dataset.

Cleaning:
- drop null values
- drop duplicate values

Feature Engineering:
- Time itself doesn't seem to determine class well. We feature a new variable which is the time difference between transaction and the precede transaction
- create a binary factor indicating transaction with large amount, with a threshold of 2000.

### Model Building: 
Around 5 models were tried and played with to get the best model that goes hand in hand with the dataset. After performing simple train and validation on the  models one was chosen for further investigation. Models trained was:
- Logstic regression (Baseline)
- SVM
- Random forest
- XGB Classifier
- Decision trees

The Best 3 Models:  Random forest , XGB Classifier and Decision trees
</br>

Dealing with Class Imbalance by SMOTE and ADAYSN.
</br>

Evaluating Cross Validation and gridsearch for the best models.
</br>

### Tools:
- Numpy 
- Pandas 
- Matplotlib 
- Seaborn 
- SqlAlchemy 
- Sklearn 
- Pickle
