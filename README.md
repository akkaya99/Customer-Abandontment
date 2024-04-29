# Customer Churn Prediction
In this study, a machine learning model was developed that can predict customers who will leave the company.

## Dataset Description
- CustomerId: Customer ID
- Gender: Gender
- SeniorCitizen: Whether the customer is a senior citizen (1, 0)
- Partner: Whether the customer has a partner (Yes, No)
- Dependents: Whether the customer has dependents (Yes, No) (Child, parent, grandparent)
- Tenure: Number of months the customer has stayed with the company
- PhoneService: Whether the customer has phone service (Yes, No)
- MultipleLines: Whether the customer has multiple lines (Yes, No, No phone service)
- InternetService: Customer's internet service provider (DSL, Fiber optic, No)
- OnlineSecurity: Whether the customer has online security (Yes, No, No internet service)
- OnlineBackup: Whether the customer has online backup (Yes, No, No internet service)
- DeviceProtection: Whether the customer has device protection (Yes, No, No internet service)
- TechSupport: Whether the customer has tech support (Yes, No, No internet service)
- StreamingTV: Whether the customer has streaming TV (Yes, No, No internet service) - Indicates if the customer uses internet service to stream television program from a third-party provider
- StreamingMovies: Whether the customer has streaming movies (Yes, No, No internet service) - Indicates if the customer uses internet service to stream movies from a third-party provider
- Contract: The contract term of the customer (Month-to-month, One year, Two year)
- PaperlessBilling: Whether the customer has paperless billing (Yes, No)
- PaymentMethod: The customer's payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- MonthlyCharges: The amount charged to the customer monthly
- TotalCharges: The total amount charged to the customer
- Churn: Whether the customer churned (Yes or No) - Customers who left within the last month or within the last quarter

## Methodology
1. **Exploratory Data Analysis (EDA):**  The general structure of the data set and the distribution of categorical and numerical variables were examined.
2. **Feature Engineering:**  Missing and outlier values ​​were edited. New variables have been created. Encoding operations have been completed.
3. **Model Building And Hyperparameter Tuning:** Studied comparatively with Logistic Regression, KNN, Decision Trees, Random Forest, XGBoost, LightGBM and CatBoost models. Hyperparameter optimizations were made.
4. **Feature Importance:** The variables that most affected the target were determined and visualized.
