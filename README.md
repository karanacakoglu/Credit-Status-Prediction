### 💳 Credit Status Prediction: A Comparative Machine Learning Study

* **Project Overview**
This repository contains a comprehensive comparative analysis of various machine learning algorithms to predict customer loan approval status. The project evaluates how financial and demographic factors—such as income, marital status, education, and credit history—influence credit eligibility.

* **🔬 Experimental Setup & Methodology**
To identify the most effective predictive model, I implemented and benchmarked 9 different classification algorithms:
* **Linear Models:** Logistic Regression.
* **Distance-Based Models:** K-Nearest Neighbors (K-NN), Support Vector Machine (SVM), and Kernel SVM.
* **Probabilistic Models:** Naive Bayes.
* **Tree-Based & Ensemble Models:** Decision Tree, Random Forest, XGBoost, and LightGBM (LGBM).

* **🛠️ Technical Workflow**
* **Data Acquisition:** Accessed the Loan Prediction Problem Dataset from Kaggle via API and manual uploads.
* **Feature Engineering:** Analyzed key financial indicators including Income, Credit History, and Marital Status to determine loan eligibility.
* **Performance Evaluation:** Compared all models based on accuracy and other classification metrics to select the optimal solution for financial risk assessment.

* **💻 Implementation (Google Colab)**
Each algorithm is documented in its own dedicated notebook for clarity:

* **💻 Colab NoteBooks (Logistic Regression Google Colab):**([Logistic Regression](https://colab.research.google.com/drive/1yWg3rQzQfUi3Fr4L0x5hG_ZISOhZ8Q-P?usp=sharing))
* **💻 Colab NoteBooks (K-Neearest Neighbors(K-NN) Google Colab):**([k-NN](https://colab.research.google.com/drive/1REq7rIvTSSTlJx3JUN9YF0bCwVdOH4lU?usp=sharing))
* **💻 Colab NoteBooks (Support Vecotr Machine(SVM) Google Colab):** ([SVM](https://colab.research.google.com/drive/1FkwArdpGPeuVYJwj3UdG3n9p2tlI-zvg?usp=sharing))
* **💻 Colab NoteBooks (Kernel SVM Google Colab):** ([Kernel SVM](https://colab.research.google.com/drive/1sQufmh4dGfh0AdvSBsqfBAbTI7cicRv2?usp=sharing))
* **💻 Colab NoteBooks (Naive Bayes Google Colab):**([Naive Bayes](https://colab.research.google.com/drive/1CJKIIM6CAhG6mcJfSqWLPun2Kg97Am0s?usp=sharing))
* **💻 Colab NoteBooks (Decision Tree Classifier Google Colab):** ([Decision Tree Classifier](https://colab.research.google.com/drive/16YfTJXUkLLwAh1j5vuZF4p9y6fOSyK0e?usp=sharing))
* **💻 Colab NoteBooks (Random Forest Classifier Google Colab):** ([Random Forest Classifier](https://colab.research.google.com/drive/1ZXf7snIDopWzd0h72rTAvJOTzICENU6W?usp=sharing))
* **💻 Colab NoteBooks (XGBoost Google Colab):** ([XGBoost](https://colab.research.google.com/drive/1kH3UZFRbJqVD_Dl7ZSlWTQRlkBaOvzMV?usp=sharing))
* **💻 Colab NoteBooks (LGBM Google Colab):** ([LGBM](https://colab.research.google.com/drive/1d8MbDPS3xfPlxHXGJzu1p_OkoZmu6Rjw?usp=sharing))

* **📊 Dataset Source:** [Loan Prediction Problem Dataset - Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
* **Dataset Note:** This dataset was used to predict a customer's loan approval status based on their financial organization details (Income, Marital Status, Education, Credit History, etc.). Access to the data in the Colab notebooks was provided via the Kaggle API or manual upload.
