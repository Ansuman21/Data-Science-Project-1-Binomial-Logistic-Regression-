# Predicting Student Dropout Trends with Linear Regression

## Overview
This project aims to analyze and predict student dropout rates based on historical data. The goal is to identify factors contributing to dropouts and provide actionable recommendations to reduce them. By leveraging predictive modeling, stakeholders can make informed decisions to improve student retention.

## Business Case
Educational institutions face challenges in maintaining student retention rates, which directly impact academic performance, reputation, and funding. By analyzing dropout trends, this project seeks to:
- Identify key predictors of student dropouts.
- Provide actionable insights to mitigate risks.
- Optimize resource allocation to at-risk students.

## Methodology
### Data Exploration
1. **Data Collection**: Gathered anonymized historical data on students, including demographic, academic, and behavioral attributes.
2. **Data Cleaning**: Addressed missing values, handled outliers, and performed exploratory data analysis (EDA) to understand trends.

### Feature Engineering
1. Normalized numerical variables for uniform scaling.
2. Encoded categorical variables using one-hot encoding.
3. Selected meaningful features based on domain knowledge and correlation analysis.

### Model Building
1. **Tried Various Models**:
   - Poisson Regression
   - Negative Binomial Regression
   - Linear Regression
   - Decision Tree Regressor

2. **Evaluation Metrics**:
   - Mean Squared Error (MSE)
   - R-Squared
   - Akaike Information Criterion (AIC)

3. **Best Model Selection**: Linear Regression was selected based on its superior performance and interpretability.

### Model Evaluation
1. Performed k-fold cross-validation to validate the model’s robustness.
2. Achieved a high R-squared value, indicating a strong relationship between predictors and dropout rates.
3. Compared actual vs. predicted values to ensure reliability.

### Visualization
- Generated plots to visualize trends and predictions:
  - Correlation heatmap
  - Actual vs. Predicted dropout counts
  - Feature importance (coefficients)

## Recommendations
1. **Enhance Student Support**:
   - Focus on students in high-risk groups identified by the model.
   - Offer targeted mentoring and counseling programs.
2. **Monitor Academic Progress**:
   - Implement early-warning systems for students struggling academically.
3. **Improve Engagement**:
   - Introduce initiatives to foster student engagement and participation.
   - Address environmental and behavioral factors that correlate with dropouts.

## Conclusion
The analysis successfully identified critical predictors of student dropouts and proposed actionable strategies to mitigate risks. By integrating these findings into institutional planning, stakeholders can enhance retention rates and support students more effectively.

## Future Work
- Expand the dataset to include external factors like socioeconomic conditions.
- Explore advanced modeling techniques like ensemble learning for improved accuracy.
- Build a real-time dashboard for dynamic dropout risk assessment.

---

## Author
**Ansuman Patnaik**  
MS in Data Science & Analytics, Yeshiva University  
Email: ansu1p89k@gmail.com
