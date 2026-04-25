1. Imports
2. Load data from Kaggle
3. Data Understanding (Statistical Analysis, Missing Values Detection, Univariate Distribution)
4. Data Preprocessing
    * Study the nature of missing values
    * Impute or Remove
    * Outlier detection
    * Deal with the anomaly (IQR, Z-score...)
    * One-hot Encode
5. EDA
    * Visualizing relationships of data
    * Correlation: Pearson, Spearman, Chi-Square
    * Findings and Insights (Important)
    * Write a Report (Findings) (Optional)

6. Train Test Split (75%-15%-15%) (Let's stratify)
    a. Consider doing Stratified K-Fold Cross-Validation (it is commonly used for classification with imbalanced classes) (use before final training)
7. Feature Engineering
8. Normalization or Scaling (StandardScaler) (Might not need)
9. Model Training with Cross Validation (GridSearchCV)
    * Logistic
    * Gaussian Naive Bayes
    * K-Nearest Neighbors
    * Decision Tree
    * Random Forest
    * XGBoost
    * CatBoost
    * Voting Classifier
10. Test ROC-AUC Scores
11. Pick the best model
12. Classification Reports
13. Hyperparameter Tuning (if have time)