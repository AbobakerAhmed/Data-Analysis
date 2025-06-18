##### Date: Tue, 29th of Apr 2025
##### Abobaker Ahmed Khidir Hassan
##### Course: IBM - Introduction to Data Analaysis
##### Platform: Coursera

# Final Project: Credit Card Fraud Early Detection and Mitigation.

### 1. List at least 5 (five) data points that are required for the analysis and detection of a credit card fraud.  
**(3 marks)**

1. **Transaction Amount** – To identify unusually large purchases.
2. **Transaction Timestamp** – To detect abnormal frequency or timing patterns.
3. **Customer’s Location / IP Address** – To compare with billing address and detect mismatches.
4. **Delivery Address** – Sudden change from usual delivery behavior can indicate fraud.
5. **Type/Category of Items Purchased** – Bulk or unusual item patterns could indicate suspicious activity.
6. **Customer ID or Card Number** – To track user-specific patterns and anomalies.
7. **Payment Method** – Using an unusual method can also flag irregularities.

---

### 2. Identify 3 (three) errors/issues that could impact the accuracy of your findings, based on a data table provided.  
**(3 marks)**

1. **Missing or Null Values** – For example, missing delivery address or transaction time makes pattern analysis difficult.
2. **Incorrect or Inconsistent Data Formats** – Such as dates written in different formats (e.g., `MM/DD/YYYY` vs `YYYY-MM-DD`) can cause errors in time-based analysis.
3. **Duplicated Records** – If the same transaction appears multiple times, it could skew frequency and amount calculations.

---

### 3. Identify 2 (two) anomalies, or unexpected behaviors, that would lead you to believe the transaction may be suspect, based on a data table provided.  
**(2 marks)**

1. **A customer usually spends $50–$100 per transaction, but suddenly spends $5,000 in one order.**
2. **The delivery address changes from the customer’s home in Khartoum to a PO Box in another country.**

---

### 4. Briefly explain your key take-away from the provided data visualization chart.  
**(1 mark)**

The chart shows that user "johnp" had a sudden and sharp increase in transaction values, reaching up to $4,000, which is a significant deviation from his earlier transactions and from others. Additionally, "ellend" had a one-time spike to nearly $5,000 in Transaction #3, while the third user "davidg" maintained consistently low transaction values throughout.

These unusual spikes in transaction value for johnp and ellend indicate potential anomalies, which could be signs of fraudulent activity.

---

### 5. Identify the type of analysis that you are performing when you are analyzing historical credit card data to understand what a fraudulent transaction looks like.  
**(1 mark)**

**Descriptive Analysis** – because it involves examining historical data to understand patterns and detect anomalies in user behavior.
