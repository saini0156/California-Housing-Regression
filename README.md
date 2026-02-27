California Housing Price Prediction 🏠


Project Overview

In this project, I implemented Multiple Linear Regression to predict median house values in California.

I transitioned from a simple model using only Median Income to a full-feature model to analyze how various socioeconomic factors influence housing prices

Technical Stack:Language:

Python

Libraries: Pandas, Scikit-Learn, Matplotlib

Dataset: Scikit-Learn fetch_california_housing

Model Performance & Insights

:Training Strategy: 80/20 Train-Test split with random_state=42 for reproducibility.Accuracy ($R^2$ Score): 0.5758Error Metric (MSE): 0.5559

Feature Importance Analysis:By analyzing the model coefficients, I found that:

Positive Impact: AveBedrms (0.7831) and MedInc (0.4486) are the strongest indicators of higher property values.

Negative Impact: Longitude and Latitude have negative coefficients, showing the significant impact of geographical location on pricing in California.

Challenges & Observations:Non-Linearity: As noted in the notebook, the data exhibits non-linear patterns, which accounts for the $R^2$ score of ~58%. This suggests that more complex models (like Random Forest or 
Gradient Boosting) may be required for higher accuracy
