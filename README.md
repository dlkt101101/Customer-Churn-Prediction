# Customer Churn Prediction x Infinite Investments Hackathon

This repository contains our team's complete data science pipeline and final submission for the UW Data Science Club Hackathon. By leveraging advanced gradient boosting architectures and robust preprocessing, our solution achieved a 90%+ F1-Score, placing us among the top competitors.

We experimented with a diverse ensemble of tree-based and gradient-boosted models to establish a strong baseline and iteratively improve performance:
* __Random Forest__: Utilized as our initial baseline model to understand feature importance mapping.
* __XGBoost__: Provided strong initial predictive power but required heavy tuning for the categorical distributions.
* __LightGBM (LGBMClassifier)__: Offered incredible training speed and solid baseline metrics.
* __CatBoost (Our Champion Model)__: Ultimately triumphed as the top performer. Because our predictor set was primarily categorical, CatBoost's native symmetric tree structure and proprietary handling of categorical features minimized information loss and out-performed the other models.
