# Telecom-Churn-Machine-Learning-Classification-Problem
OVERVIEW:

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. 
In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. 
Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition. 
For many incumbent operators, retaining high profitable customers is the number one business goal. 
To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

THE GIVENS
1) There are two main models of payment in the telecom industry - postpaid and prepaid. 
In the postpaid model, when customers want to switch to another operator, they usually inform the existing operator to terminate the services, and you directly know that this is an instance of churn. 
However, in the prepaid model, customers who want to switch to another network can simply stop using the services without any notice, and it is hard to know whether someone has actually churned or is simply not using the services temporarily.

2) Various ways to define churn: Revenue based churn (not using revenue generating facilities such as mobile internet, outgoing calls, etc.) and Usage based churn (Customers who have not done any usage at all)

3) In the Indian and the Southeast Asian market, approximately 80% of revenue comes from the top 20% customers (called high-value customers). Thus, if we can reduce churn of the high-value customers, we will be able to reduce significant revenue leakage.

4) Customer Behaviour: Customers usually do not decide to switch to another competitor instantly, but rather over a period of time. In churn prediction, we assume that there are three phases of customer lifecycle :  

  **a) The ‘good’ phase:** *Customer is happy with the service and behaves as usual.*

  **b) The ‘action’ phase:** *The customer experience starts to sore in this phase, for e.g. he/she gets a compelling offer from a  competitor, faces unjust charges, becomes unhappy with service quality etc. In this phase, the customer usually shows different behaviour than the ‘good’ months. Also, it is crucial to identify high-churn-risk customers in this phase, since some corrective actions can be taken at this point (such as matching the competitor’s offer/improving the service quality etc.)*

  **c) The ‘churn’ phase:** *In this phase, the customer is said to have churned. You define churn based on this phase. Also, it is important to note that at the time of prediction (i.e. the action months), this data is not available to you for prediction. Thus, after tagging churn as 1/0 based on this phase, you discard all data corresponding to this phase.*

BUSINESS OBJECTIVE:

The business objective is to predict the churn in the last month using the features from the first three months. To accomplish this business objective, following key points are noteworthy:

1) It is important to understand the typical customer behaviour during churn.
2) It is expected of us to analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.
3) To use the usage-based definition to define churn.
