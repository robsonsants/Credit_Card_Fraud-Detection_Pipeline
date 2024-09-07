## Pipelines used for the analysis of machine learning algorithms in the binary classification problem for credit card fraud.

Dataset

This work uses the dataset called IEEE-CIS Fraud Detection https://www.kaggle.com/competitions/ieee-fraud-detection, which was designed to enable the construction and evaluation of detection systems of fraud in e-commerce. This dataset is made up of two main tables: the transaction table and the identity table. The transaction table contains crucial information about each transaction, including the transaction amount, the credit card used, the date and time of the transaction, as well as other relevant attributes. The identity table provides additional data about the individuals involved in transactions, including demographic characteristics and information about the devices used by users.

The IEEE-CIS Fraud Detection dataset includes 434 attributes, of which 400 are anonymized (V1 to V339) in order to protect the privacy of users and institutions. Each row in the transaction table represents a specific electronic transaction. Each transaction has a label, which can take on two values indicating: legitimate transaction or fraudulent transaction. In this sense, the dataset can be used to build binary classifiers. As the data set is quite large and unbalanced, we only used a part of the data, more precisely a subset formed by the train_identity and the train_transaction, thus forming a new data set, which will be used in the subsequent stages of this work.

The approach designed to detect fraud in credit card transactions is detailed in the image below. 

Figure illustrates the machine learning architecture of the proposed approach.

![ml_1](https://github.com/robsonsants/Credit_Card_Fraud-Detection_Pipeline/assets/32533017/5fd8863a-c86d-4918-9be8-4e3dc9c8221d)
