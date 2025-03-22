# Movie_Rating_Prediction
IMDb Movie Rating Prediction Using Machine Learning

• Built a structured pipeline for data preprocessing, including handling missing values, fixing data types,
one-hot encoding categorical variables, and scaling numerical features with MinMax Scaler to ensure
data quality for machine learning.

• Identified highly skewed features and applied the IQR method to remove outliers, visualized with box
plots before & after removal for data integrity.

• Performed univariate, bivariate, and multivariate analysis to understand rating distributions, trends,
and correlations. Identified top-rated directors, trending genres, and rating patterns over time. Used
correlation heatmaps, pair plots, and statistical insights to detect multicollinearity and uncover key
relationships within the data.

• Implemented Linear Regression (Train R² = 1.000, Train MSE = 0.000, Test R² = 0.128, Test MSE =
0.021) and detected overfitting, then applied Random Forest Regressor (Train R² = 0.900, Train MSE =
0.0025, Test R² = 0.255, Test MSE = 0.018), significantly improving generalization.

• Identified key factors influencing movie ratings using Random Forest feature importance. 'Year,' 'Votes,'
and 'Duration' had the most significant impact, helping refine model interpretability and potential
feature selection for future improvements.
