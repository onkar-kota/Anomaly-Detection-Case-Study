# Anomaly Detection in Transactions

Anomaly detection is a critical aspect of data analysis that involves identifying patterns or instances that deviate significantly from the expected behaviour within a dataset. The challenge is to develop robust anomaly detection models that can accurately distinguish between normal and abnormal data points, thereby assisting in fraud detection, fault diagnosis, and outlier identification.

Here your goal is to build a robust model that can accurately distinguish legitimate transactions from potential anomalies, thus safeguarding the financial system from fraudulent activities and ensuring customer trust.

The dataset contains information about various financial transactions, each represented by several features:

- **Transaction_ID**: Unique identifier for each transaction.
- **Transaction_Amount**: The monetary value of the transaction.
- **Transaction_Volume**: The quantity or number of items/actions involved in the transaction.
- **Average_Transaction_Amount**: The historical average transaction amount for the account.
- **Frequency_of_Transactions**: How often transactions are typically performed by the account.
- **Time_Since_Last_Transaction**: Time elapsed since the last transaction.
- **Day_of_Week**: The day of the week when the transaction occurred.
- **Time_of_Day**: The time of day when the transaction occurred.
- **Age**: Age of the account holder.
- **Gender**: Gender of the account holder.
- **Income**: Income of the account holder.
- **Account_Type**: Type of account (e.g., personal, business).

## Task

Your task is to develop an effective anomaly detection model that can identify suspicious or fraudulent financial transactions based on the provided features. The solution should be capable of accurately flagging transactions that deviate significantly from the expected behaviour while minimizing false positives that could inconvenience legitimate customers.