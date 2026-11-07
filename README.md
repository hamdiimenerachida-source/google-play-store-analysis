## Google Play Store App Installs Prediction

An end-to-end predictive analytics project built using **Altair RapidMiner Studio**. The project models and predicts mobile application popularity (`log_Installs`) based on store features, app characteristics, and user engagement metrics.

### Key Highlights
- **Data Engineering:** Automated missing value imputation, text cleaning, skewness reduction via logarithmic transformations, and duplicate handling.
- **Modeling:** 10-Fold Cross-Validation using **Gradient Boosted Trees** (300 trees, learning rate 0.1, depth 5).
- **Performance:** Achieved an **$R^2$ of 0.936** during cross-validation and evaluated generalization on an independent 2021 dataset.
