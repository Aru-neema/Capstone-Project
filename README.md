# Capstone-Project

Health Insurance Cost - Consumer Analysis and Cost Prediction

Sometimes timely treatment becomes super costly for people if they are not covered under the insurance. The companies in the medical insurance also want to reduce their risk by optimizing the insurance cost. Hence, the objective of this project is to profile consumers by understanding their health parameters through various data analysis techniques and build a model to estimate optimum insurance cost.  The business opportunity lies in accurate estimations of insurance cost while social opportunity in providing suitable insurance cover. 




## Case Steps
1. First downloaded and uploaded the required libraries for performing data cleaning and exploratory data analysis and visual data inspection
2. Treated the data for missing values using winsorisation and removed unwanted variables. Also scaled the data for future analytical process
3. Perfomed kmeans clutering to identify cluster of insurance customer. WSS plot and silhoutte score helped in identifying the clusters. 
3. Extracted business insights through uni and bi variate analysis of the two clusters
4. Build linear regression, OLS regression, random forest and KNN models to predict the insurace cost of customers based on their quantifyable health indicators. OLS regression also helped in identifying the significance of each 
predictor variable on predicted variable 
5. Ensemble modelling, AdaBoost and Gradient Boost was used to conduct model tuning
6. On comparing the RMSE value on test data, gradient descent gave the bet result

## Result
Many of the models used to predict the insurance cost were proving to be overfit. However, relatively, Gradient Descent gave the best result. 
6 variables were identified which had significant impact on insurance cost and must be considered to determine insurance cost 

## Skills and Tools Used

Cluster Analysis, Decision Trees, Python, Random Forest, TABLEAU
