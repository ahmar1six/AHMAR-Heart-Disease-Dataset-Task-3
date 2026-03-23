**Task Objective**

Develop a predictive model to classify patients at risk of heart disease using clinical health metrics, and explore feature relationships through visual analysis.

**Dataset Used**
Name: UCI Heart Disease Dataset (heart_disease_uci.csv)

Records: 920 patients

Features: 14 clinical attributes (age, sex, chest pain type, blood pressure, cholesterol, resting ECG, max heart rate, ST depression, etc.)
Target: has_disease (binary: 1 = risk, 0 = healthy)

**Models Applied**
Decision Tree Classifier with max_depth=5 to prevent overfitting.
Feature Engineering: One-Hot Encoding for categorical variables.
Evaluation Metrics: Accuracy, ROC-AUC, Confusion Matrix, Classification Report.

**Key Results and Findings**
Accuracy: 82.1% with strong ROC-AUC (≈0.84).

Top Predictors: Chest pain type (cp), ST depression (oldpeak), number of major vessels (ca).

Visual Insights: Histograms and boxplots reveal feature distributions and outliers; top 10 features show the most predictive clinical metrics.

Clinical Implication: Model effectively identifies high-risk patients, supporting early screening and intervention.
