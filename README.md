# Assignment_Regression_with_Machine_Learning_Regressors

```mermaid
flowchart TD
    A[Start: Load Dataset] --> B[Data Understanding]
    B --> B1[Show first few rows]
    B --> B2[Identify input features & target]
    B --> B3[Check data types]
    B --> B4[Handle missing values & duplicates]

    B4 --> C[Exploratory Data Analysis (EDA)]
    C --> C1[Plot target variable distribution]
    C --> C2[Visualize feature-target relationships]
    C --> C3[Compare categorical features (if any)]
    C --> C4[Correlation heatmap]

    C4 --> D[Data Preprocessing]
    D --> D1[Encode categorical variables]
    D --> D2[Scale numerical features]
    D --> D3[Impute missing values]
    D --> D4[Train-test split]

    D4 --> E[Model Building]
    E --> E1[Train Decision Tree Regressor]
    E --> E2[Train Random Forest Regressor]
    E --> E3[Train AdaBoost Regressor]
    E --> E4[Train XGBoost Regressor]
    E --> E5[Train CatBoost Regressor]

    E1 --> F1[Evaluate using MAE, MSE, RMSE, R²]
    E2 --> F2
    E3 --> F3
    E4 --> F4
    E5 --> F5

    F1 --> G[Model Optimization]
    F2 --> G
    F3 --> G
    F4 --> G
    F5 --> G

    G --> G1[Hyperparameter tuning (e.g. RF & XGB)]
    G1 --> G2[Compare tuned vs default performance]
    G2 --> G3[Discuss overfitting/underfitting]

    G3 --> H[Final Evaluation & Comparison]
    H --> H1[Summary table of regressors]
    H --> H2[Actual vs Predicted plots]
    H --> H3[Feature importance plots]

    H3 --> I[End]

```
