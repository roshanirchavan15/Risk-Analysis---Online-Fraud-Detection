# Online-Fraud-Detection
Fraudulent transactions can have serious consequences for both customers and businesses. For customers, fraudulent transactions can result in financial losses, damage to credit scores, and identity theft. For businesses, fraudulent transactions can result in reputational damage, financial losses, and legal liabilities. Therefore, it is essential for businesses to have effective fraud detection and prevention mechanisms in place. 

The project utilizes transaction history datasets to analyze customer behaviors and identify any deviations from usual spending patterns, which could indicate fraudulent activities. By preventing fraudulent transactions, businesses can improve customer trust, minimize financial losses, and protect their reputation in the market.   

Data set is taken from Kaggle-https://www.kaggle.com/datasets/bannourchaker/frauddetection?select=transactions_train.csv

Data Transformation: IsFraud is the target variable, with Class '0' constituting approximately 99.88% and Class '1' only 0.12% of the total samples The approach used to address the imbalanced datasets is to oversample the minority class. The simplest approach involves duplicating examples in the minority class, although these examples don’t add any new information to the model. Instead, new examples can be synthesized from the existing examples. This is a type of data Augmentation for the minority class and is referred to as the Synthetic Minority Oversampling Technique or SMOTE for short.

Data Modelling:
By using data mining techniques to analyze transaction data, it is possible to identify patterns and trends that may indicate fraudulent activity in mobile payment applications. This can help businesses prevent fraud and protect their customers from financial losses.
Random Forest and Naive Bayes, have similar requirements for data preprocessing. 
Both models can handle categorical and numerical features, and they do not require feature scaling. 
Naive Bayes is generally faster and requires less memory than Random Forest, especially for large datasets. 
Naïve Bayes is easier to interpret.

