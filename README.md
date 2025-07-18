  # Arch-Technology-Internship

# Task 1 House Price Prediction Notebook
Objective
Predict California housing prices using Random Forest Regression and Linear Regression, comparing their performance.
Dataset
Source: california_housing_test.csv (3,000 entries, 9 features)
Key Features:
longitude, latitude (location)
total_rooms, population (property & neighborhood details)
median_house_value (target variable)
Key Steps
Data Preparation
Checked for missing values (none found).
Selected relevant features based on correlation analysis.
Model Training & Evaluation
Random Forest Regression:
RMSE: 63,388 (lower error)
R²: 0.68 (better fit)
Top Features: Latitude & Longitude most important.
Linear Regression:
RMSE: 89,872 (higher error)
R²: 0.36 (poorer fit)
Comparison
Random Forest performed better (lower RMSE, higher R²).
Visualizations (scatter plots, bar charts) confirmed its superiority.
Conclusion
Random Forest is more effective for this housing price prediction task due to its ability to capture non-linear relationships.




#    Task 2 Iris Flower Classification 

Objective
Classify iris flowers into three species (setosa, versicolor, virginica) using Logistic Regression and Random Forest Classifier, comparing their performance.
Dataset
Source: IRIS.csv (150 samples, 5 features)
Features:
sepal_length, sepal_width (structural measurements)
petal_length, petal_width (flower measurements)
species (target: encoded as 0, 1, 2)
Key Steps
Data Preparation
Checked for missing values (none found).
Encoded species labels (setosa→0, versicolor→1, virginica→2).
Correlation heatmap showed strong relationships between petal features.
Model Training & Evaluation
Logistic Regression:
Accuracy: 97% 
Confusion Matrix: Minimal misclassifications (1 error).
Random Forest:
Accuracy: 90% 
Confusion Matrix: More errors (2 misclassified samples).
Visual Comparisons 
Decision Boundaries:
Logistic Regression: Linear separation.
Random Forest: Complex, non-linear boundaries.
Bar Chart: Logistic Regression outperformed Random Forest.
Conclusion
Logistic Regression achieved higher accuracy (97%) due to simpler, linearly separable data.
Random Forest (90%) was slightly worse but could handle more complex patterns.
Key Insight: For this dataset, a linear model (Logistic Regression) was more effective.
