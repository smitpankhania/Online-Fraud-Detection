# Online Payment Fraud Detection
Online payment fraud detection is a common problem that businesses face when processing payments online. The goal is to detect fraudulent transactions before they are processed and approved, in order to prevent financial losses and protect the business and its customers.

One approach to tackle this problem is <br>

Transaction monitoring : This involves using machine learning algorithms to analyze transactions in real-time, looking for patterns or anomalies that may indicate fraud. For example, a sudden increase in the number of transactions or a change in transaction patterns may indicate fraudulent activity.

Hence, inorder to identify online payment fraud with machine learning, we need to train a machine learning model for classifying fraudulent and non-fraudulent payments.

About Dataset
There are 6362620 rows and 11 columns in our dataset.

* step: represents a unit of time where 1 step equals 1 hour
* type: type of online transaction
* amount: the amount of the transaction
* nameOrig: customer starting the transaction
* oldbalanceOrg: balance before the transaction
* newbalanceOrig: balance after the transaction
* nameDest: recipient of the transaction
* oldbalanceDest: initial balance of recipient before the transaction
* newbalanceDest: the new balance of recipient after the transaction
* isFraud: fraud transaction
* isFlaggedFraud: Flagged fraud transaction
