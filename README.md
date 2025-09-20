# Best Machine Ever – Predictive Maintenance with Machine Learning

This project explores how supervised machine learning can reduce costly factory downtime by predicting equipment failures before they occur. Using the AI4I 2020 Predictive Maintenance dataset, our team engineered new features—such as temperature differential and power (torque × rotational speed)—and applied SMOTE to correct heavy class imbalance.

We trained and compared Decision Tree, Random Forest, and XGBoost classifiers, optimizing for high recall to minimize false negatives. The final recall-tuned XGBoost model achieved a 97.18% F1 score and 99% recall with less than a 1% train–test gap, showing strong generalization. SHAP analysis highlighted temperature difference, power, and tool wear as the most critical predictors of machine failure.

Key deliverables include:
- A reproducible Python pipeline for data cleaning, feature engineering, model tuning, and evaluation.

- Visualizations of feature importance, SHAP plots, and ROC/PR curves.

- Actionable insights for deploying predictive maintenance strategies in real manufacturing settings.

- By bridging raw sensor data with interpretable ML models, this project demonstrates how data-driven maintenance can enhance safety, efficiency, and cost savings in industrial operations.
