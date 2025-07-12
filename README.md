\# 🫀 CardioRisk V1



\*\*CardioRisk V1\*\* is a machine learning project for early heart disease risk prediction. This project combines two heart disease datasets from UCI and Kaggle, applies advanced preprocessing techniques, and trains eight different ML models to evaluate the best performing one.



\## 🧠 Project Goals

\- Predict heart disease risk using clinical data.

\- Identify the best-performing ML model using cross-validation and performance metrics.

\- Offer a clean, documented process for replicability and extension.

\- Provide a prototype UI for healthcare practitioners.



\## 📊 Datasets

\- \*\*UCI Cleveland Heart Disease Dataset\*\*

\- \*\*Kaggle Heart Disease Dataset\*\*

\- Combined and cleaned to form a unified dataset with rich patient features.



\## ⚙️ Features

\- Missing value imputation using \*\*Random Forest Imputer\*\*

\- Data normalization using \*\*StandardScaler\*\* and \*\*QuantileTransformer\*\*

\- 8 classification models trained and evaluated:

&nbsp; - Logistic Regression

&nbsp; - KNN

&nbsp; - SVM

&nbsp; - Decision Tree

&nbsp; - Random Forest

&nbsp; - Gradient Boosting

&nbsp; - AdaBoost

&nbsp; - XGBoost



\## 🏆 Best Performing Model

\- \*\*XGBoost\*\*

\- Accuracy: 92%

\- F1 Score: 96%

\- ROC-AUC: 98%



\## 🛠 Tech Stack

\- Python

\- scikit-learn

\- xgboost

\- pandas, matplotlib, seaborn

\- Streamlit (UI Prototype)



\## 📁 Files Included

| File | Description |

|------|-------------|

| `cardiorisk\_v1.py` | Main script with full preprocessing, modeling, and evaluation |

| `CardioRisk-ProjectReport.pdf` | Full academic report |

| `requirements.txt` | Python dependencies |

| `.gitignore` | Standard Python ignores |





