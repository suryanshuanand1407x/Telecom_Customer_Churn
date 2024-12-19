**Customer Churn Prediction**
**Overview**

This project aims to predict customer churn using logistic regression. Customer churn refers to when customers stop doing business with a company. Predicting churn helps businesses take proactive measures to retain customers, reducing revenue loss and improving customer satisfaction.

Using a telecom dataset, we performed data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and optimization to build a robust churn prediction model.

**File Structure**

Customer_Churn_Prediction/
│
├── data/
│   ├── raw/                  # Raw dataset
│   ├── processed/            # Preprocessed dataset and saved feature names
│   └── results/              # Predictions and evaluation results
│
├── notebooks/
│   ├── 1_data_exploration.ipynb       # EDA and insights
│   ├── 2_data_preprocessing.ipynb     # Data cleaning and preprocessing
│   ├── 3_exploratory_data_analysis.ipynb  # Further visualizations
│   ├── 4_model_training.ipynb         # Logistic regression training
│   ├── 5_model_tuning.ipynb           # Hyperparameter tuning
│   └── 6_model_deployment.ipynb       # Deployment and predictions
│
├── models/
│   ├── logistic_regression_model.pkl        # Initial model
│   └── logistic_regression_best_model.pkl   # Optimized model
│
├── reports/
│   └── churn_prediction_report.pdf    # Insights and findings
│
├── README.md                   # Project overview and instructions
└── requirements.txt            # Python dependencies
