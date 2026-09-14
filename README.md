# Clinical Risk & Business Classification Modeling

## 1. Executive Summary
Predictive classification pipeline built to identify high-risk clinical profiles from clinical and physiological indicators. The project benchmarks baseline models against ensemble techniques, optimizing for recall to minimize false negatives[cite: 2].

## 2. Workflow & Evaluation
* **Exploratory Data Analysis:** Analyzed feature correlations across physiological variables (e.g., age, resting BP, cholesterol, maximum heart rate).
* **Modeling Benchmark:** Built and evaluated supervised classifiers, comparing Logistic Regression with Random Forest ensembles[cite: 2].
* **Performance Metrics:** Evaluated models using Precision, Recall, F1-Score, and ROC-AUC curves[cite: 2].
* **Hyperparameter Tuning:** Tuned tree estimators and decision thresholds via `GridSearchCV` to optimize sensitivity on high-risk classifications[cite: 2].

## 3. Tech Stack
* Python, Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn[cite: 2]
