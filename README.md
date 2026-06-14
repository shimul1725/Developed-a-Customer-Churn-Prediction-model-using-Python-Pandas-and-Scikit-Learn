Data Preprocessing & Methodology
"In this project, we successfully implemented One-Hot Encoding using ColumnTransformer to handle the categorical features. To prevent any data leakage, we strictly followed the best practices by applying fit_transform exclusively on the training set and transform on the testing set."

Model Evaluation & The Winner
"We explored three distinct machine learning algorithms: Logistic Regression, Random Forest, and XGBoost. Based on our comprehensive performance dashboard, Logistic Regression emerged as the winner for this specific dataset. It achieved the highest overall accuracy of 81.6% and outperformed the other models with a Class 1 F1-Score of 0.642."

Key Performance Insights
XGBoost: "While XGBoost is typically highly effective for tabular data, it fell slightly short of Logistic Regression here, achieving an 81.0% accuracy and showing a lower capability in identifying the minority class."

Random Forest: "Random Forest underperformed compared to the other two, delivering the lowest overall accuracy of 77.9% and struggling significantly with Class 1 predictions."
