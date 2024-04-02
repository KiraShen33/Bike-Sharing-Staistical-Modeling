# Bike Sharing Analysis Staistical Modeling

## Introduction
This project examines the bike sharing systems to analyze user behavior and understand usage patterns and preferences. Utilizing the UCI Machine Learning Repository's dataset with 17 features and 17,379 data points, the goal is to predict the total count of rented bikes. Insights from this analysis are aimed at helping bike sharing providers and urban planners to enhance system efficiency and promote sustainable transportation.

## Data Source
The dataset used in this project is from the UCI Machine Learning Repository's bike sharing dataset.

## Exploratory Data Analysis (EDA)
During the initial EDA, redundant variables such as instant and date were dropped. Seasonal variations in rental counts were observed, and the target variable cnt was found to be right-skewed. A log transformation was applied to the target variable for further analysis. A correlation heatmap guided the exclusion of highly correlated variables to avoid multicollinearity.

## Methodology
1. Simple Linear Regression: Utilized for its interpretability, the model was adjusted based on forward feature selection. Log transformation was applied to the target variable to meet linear regression assumptions.

2. Principal Component Analysis (PCA): An unsupervised method to reduce data dimensionality, maintaining maximum variance. It also helped in addressing multicollinearity and overfitting.

3. Lasso Linear Regression: Employed to address potential overfitting and highlight feature importance through lasso shrinkage.

## Results
The study compared three models: Simple Linear Regression, PCA Linear Regression, and Lasso Linear Regression. The PCA Linear Regression model emerged as the champion model, showing the lowest Mean Squared Error (MSE) and highest R-squared value.

## Key Insights
- AIC, BIC, LASSO, and PCA indicated that season, temperature, holiday, humidity, hours, and years are significant predictors of bike rentals.
- Surprisingly, variables indicating population changes, such as working days and holidays, had a lesser impact on bike rentals.
- Favorable weather conditions increase the likelihood of bike rentals.

## Conclusion
The analysis concluded that comfortable weather is a significant factor for bike rentals, and some expected influences 

## Contributors
- Qinmiao Deng*
- Kira Shen*
- Xinbei Yu*
- Kaishuo Zhang*
- Qi Zhao*
*Each person equally contributed to this project.

Contact: {qinmiao_deng, ruiqi_shen, xinbei_yu, kaishuo_zhang, qi_zhao}@brown.edu

