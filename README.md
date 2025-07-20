🫀 CardioRisk V1

CardioRisk V1 is a machine learning project for early heart disease risk prediction.
It combines two heart disease datasets (UCI and Kaggle), applies advanced preprocessing techniques, and evaluates eight ML models to determine the best-performing one.

---

1. Project Goals

   * Predict heart disease risk using clinical data.
   * Identify the best-performing ML model using cross-validation and evaluation metrics.
   * Offer a clean, documented pipeline for replicability and extension.
   * Provide a prototype UI for healthcare practitioners.

2. Datasets Used

   * UCI Cleveland Heart Disease Dataset
   * Kaggle Heart Disease Dataset
   * Combined and cleaned to form a unified dataset with rich patient features.

3. Features

   * Missing value imputation using Random Forest Imputer.
   * Data normalization using StandardScaler and QuantileTransformer.
   * Eight classification models trained and compared:

     * Logistic Regression
     * K-Nearest Neighbors (KNN)
     * Support Vector Machine (SVM)
     * Decision Tree Classifier
     * Random Forest Classifier
     * Gradient Boosting Classifier
     * AdaBoost Classifier
     * XGBoost Classifier

4. Best Performing Model

   * Model: XGBoost Classifier
   * Accuracy: 92%
   * F1 Score: 96%
   * ROC-AUC: 98%

5. **Tech Stack**

   * Python 3.x
   * scikit-learn
   * xgboost
   * pandas, matplotlib, seaborn, plotly
   * Streamlit (for UI prototype)

6. **Files Included**

   * `cardiorisk_v1.py` – Main script with full preprocessing, modeling, and evaluation
   * `CardioRisk-ProjectReport.pdf` – Full academic report and documentation
   * `requirements.txt` – Python dependencies
   * `.gitignore` – Standard Python ignore rules

7. **How to Run**

   * Install dependencies:
     pip install -r requirements.txt
   * Run the script:
     python cardiorisk\_v1.py

8. **Authors & Credits**

   * Ayham Emad Mohammad Ali
   * Omar Hussein Jankhot
   * Supervised by: Dr. Mohammad Alhawarat
   * Middle East University — Graduation Project 2025

---
