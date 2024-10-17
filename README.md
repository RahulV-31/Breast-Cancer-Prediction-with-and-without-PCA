# Breast-Cancer-Prediction-with-and-without-PCA
This project compares the accuracy of a Logistic Regression model trained on the breast cancer dataset with and without Principal Component Analysis (PCA). The goal is to demonstrate the effect of dimensionality reduction on model performance.

This project encompasses Exploratory Data Analysis (EDA), dimensionality reduction, and Logistic Regression to build and compare models.

🔬 Project Breakdown:
Dataset: Utilized the Breast Cancer dataset, featuring 30 numerical attributes related to cell nuclei.
EDA:
Analyzed data distribution and relationships between features.
Visualized correlations to identify redundant features.
Explored the balance between benign and malignant cases.
Preprocessing:
Standardized the data to ensure optimal performance for PCA and Logistic Regression.
Model 1:
Logistic Regression trained on the original 30 features.
Accuracy: 98.25%
Model 2:
Applied PCA to reduce the feature space to 8 principal components.
Logistic Regression trained on the reduced dataset.
Accuracy: 98.83%
Comparison:
PCA not only reduced the dimensionality but also slightly enhanced the model’s accuracy.
💡 Key Learnings:
PCA Benefits:
Dimensionality Reduction: Simplifies models by reducing the number of features.
Performance Enhancement: Eliminates noise and redundant information, leading to better model accuracy.
Model Performance: Even with fewer features, the PCA-enhanced model outperformed the original, showcasing the power of effective feature selection.
📊 Visual Insights:
Correlation Heatmap: Identified highly correlated features, guiding the PCA process.
Target Distribution: Balanced insights into benign vs. malignant cases.
Pairplot: Visualized relationships between key features and the target variable.
📈 Results:
Accuracy without PCA: 98.25%
Accuracy with PCA: 98.83%
