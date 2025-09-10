Project Note: Student Performance Predictor

This project uses the UCI Student Performance Dataset to predict whether a student will pass or fail their final exam, based on demographic, social, and academic attributes.

🔹 Key Steps:

Data Preprocessing:

Encoded categorical features using One-Hot Encoding

Scaled numerical features with StandardScaler

Target Engineering:

Created a binary target variable pass (1 = G3 ≥ 10, 0 = G3 < 10)

Dimensionality Reduction:

Applied PCA and t-SNE for visualization of student distributions

Model Training:

Implemented a baseline Random Forest Classifier

Evaluated performance with a classification report and confusion matrix

Model Persistence:

Saved trained model and preprocessing pipeline with joblib

🔹 Insights:

Social and academic factors strongly influence student outcomes.

Visualization (t-SNE) revealed clusters separating pass vs. fail students.

Random Forest provides a solid baseline, but results can be improved with feature engineering and hyperparameter tuning.

🔹 Next Improvements:

Experiment with other models (Logistic Regression, Gradient Boosting, XGBoost).

Add feature engineering (alcohol average, study support score).

Perform hyperparameter tuning with GridSearchCV.

Use SHAP for explainable AI insights.

Deploy as a simple Gradio web app to interactively predict student performance.
