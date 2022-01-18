# Marketing-Analysis

Objective of the Project:

Study the spend behaviour and past campaign responses to build a response model that can be used to give a strategy that enhances the response rates and improves
profitability of marketing campaign.

BaseLine Event Rate:

The response rate from the data is 14.9%.

Algorithm used:

In this project we have used DecisionTree,Random Forest,Logistic Regression and Gradient Boosting Algorithm.

Final Model Building:

Among the models that we tried building the GBM Algorithm performed the best in terms of F1_Score, Area under ROC Curve and overall Model Gini

Therefore we have kept GBM as the final model algorithm.

Grid Search CV parameter:

Maximum Depth of Tree - 3

Minimum Sample Size for Nodes to be Split - 75 Observations

Model Performance Measures:

Accuracy - 0.85

Precision - 0.52

Recall - 0.30

F1 Score - 0.38

AUC - 0.62

Top 10 features from the model:

Income	0.203555
AcceptedCmp3_1	0.201680
MntMeatProducts	0.199366
Cust_Tenure_9.0	0.072827
MntFishProducts	0.055813
MntFruits	0.040554
NumDealsPurchases_10	0.025441
NumCatalogPurchases_10	0.024639
Marital_Status_Single	0.024426
Marital_Status_Together	0.022773

APT Strategy Framework:

Audience-Top 3 Deciles(Best 30% of the customer)
         70% Reduction in the Marketing Cost
         4.2% higher time the Response rate

Prioritization- 
                
Engagement	 High	    Low
spend_level		
High Spend	  146	     22
Low Spend	    356	     148

Treatment-Best offers should be provide in Wines/Meat/Fish/Gold.

