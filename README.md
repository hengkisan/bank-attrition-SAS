# Predictive Analysis of Bank Customer Attrition from Credit Card Usage Patterns

## 📚 Introduction
This study delves into the critical issue of customer attrition, particularly within the banking sector and focusing on credit card usage. The problem statement emphasizes the impact of customer churn on the sustainability of bank institutions, highlighting the need for effective strategies to mitigate attrition. The objectives include developing precise machine learning models, identifying factors influencing attrition, and providing actionable insights for bank institutions.

## 💻 Tools and Analysis
SAS Enterprise Miner is utilized for data mining and predictive modeling processes. The dataset, sourced from Kaggle.com, consists of 10,127 observations with 19 independent variables and a binary target variable indicating attrition status. Exploratory data analysis (EDA) is conducted using StatExplore and MultiPlot functionalities to understand variable distributions and correlations.

![image](https://github.com/hengkisan/bank-attrition-SAS/assets/122197570/eacf7c54-93e4-46c6-b995-10d83ff9b343)

Data preparation involves handling skewness, under-sampling for class imbalance, and partitioning the dataset for training and validation. Feature selection is performed using logistic regression, and various machine learning models such as Decision Tree, HP Tree, HP Forest, and Neural Networks are built to predict customer attrition.

![image](https://github.com/hengkisan/bank-attrition-SAS/assets/122197570/5207066c-8659-4a53-86e4-f6a5ff8f876d)

## 💡 Conclusion
The findings from the analysis reveal several significant insights. Tree-based models, particularly HP Forest on a filtered dataset, demonstrate superior performance in predicting attrition with a misclassification rate as low as 5.5%. Feature selection enhances model accuracy by reducing noise and improving generalization. Key factors influencing attrition include credit card usage patterns, transaction counts, and revolving balances. Customers exhibiting under-utilized credit cards and those involved in excessive spending show distinct attrition tendencies.

![image](https://github.com/hengkisan/bank-attrition-SAS/assets/122197570/88258f39-e0d7-4433-bc7a-4aab42840c11)

The study concludes by recommending personalized strategies for customer retention based on identified behaviors. For customers with under-utilized credit cards, personalized offers and enhanced communication are suggested, while interventions for customers with excessive spending may include financial counseling and proactive alerts. These insights provide valuable guidance for bank institutions in developing effective countermeasure strategies to address customer attrition.
