# Sales-Prediction
The increasing competition in the market needs accurate predictions of sales to 
formulate effective marketing strategies. This project aims to develop a predictive 
model that predicts sales based on expenditures on various marketing platforms, 
namely TV, radio, and newspapers.  
The primary objectives are: 
● To define the relationship between marketing spend and sales. 
● To implement predictive models using various Machine Learning 
Algorithms. 
● To evaluate the models' performance and draw actionable insights. 
Problem Statement: Despite substantial investments in marketing, many 
companies frequently find it challenging to determine how effective these 
expenditures are in driving sales. This study addresses this gap by analyzing 
historical data to predict future sales based on advertising spend. 

Implemented approach or Algorithm:  
 
Algorithms Explanation: 
● Linear Regression finds the best-fitting straight line that predicts sales based 
on a single factor (like TV spend). It estimates how much sales change with 
each unit increase in the factor. 
● Decision Trees split the data into branches based on different features, creating 
rules to predict sales. Each split is made to reduce error, and the final prediction 
is the average value of the target variable in the leaf node. 
● Random Forest builds many decision trees on random subsets of the data and 
averages their predictions. This reduces overfitting and improves accuracy. 
● k-Nearest Neighbors (k-NN) makes predictions by looking at the K closest 
data points in the dataset. It averages their sales values to predict the sales for a 
new point, based on similarity. 
 
Justification for Selection: Using a variety of algorithms for sales prediction 
allows for a comprehensive analysis of different data characteristics and 
relationships. Linear Regression is ideal for simple, linear relationships with a 
single predictor. Decision Trees excel in handling complex, non-linear 
relationships and offer easy interpretability, whereas Random Forest enhances 
accuracy and reduces overfitting by averaging predictions from multiple trees. 
Lastly, k-Nearest Neighbors (k-NN) captures local patterns by predicting sales 
based on the closest previous instances. This combination of algorithms ensures a 
reliable approach to accurately predicting sales across various scenarios. 
 
Working: The implemented algorithm follows these steps: 
1. Data Collection: Gather data from the Kaggle dataset on advertising 
expenditures and sales. 
2. Data Preprocessing: 
○ Check for Missing Values: Identify and handle any missing data. 
○ Check for Duplicate Values: Remove duplicates to ensure data integrity. 
○ Check for Outliers: Identify extreme values that could skew results. 
3. Exploratory Data Analysis (EDA): 
○ Visualize the distribution of sales. 
○ Analyze relationships between sales and independent variables. 
4. Model Building: Train the models on the data. 
5. Prediction: Use the trained models to predict sales based on marketing spend. 
