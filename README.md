# 📊 Customer Churn Analysis & Prediction

<p align="left">
  <img src="[https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)" alt="Python" />
  <img src="[https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)" alt="Pandas" />
  <img src="[https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)" alt="Scikit-learn" />
  <img src="[https://img.shields.io/badge/Matplotlib-11557c?style=flat-square](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)" alt="Matplotlib" />
  <img src="[https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white)" alt="Jupyter" />
</p>

## 📝 Project Overview
This project is an end-to-end machine learning and data analytics study developed to predict **customer churn**. It encompasses comprehensive data analysis, visualization, feature engineering, and model development processes. The findings are reported to support data-driven business decisions.

## 📂 File Structure & Processes
The project is divided into different Jupyter Notebook files to process the data step-by-step:

* 📁 **`dataset/`**: The folder containing the original customer dataset used in the analysis.
* 📓 **`churn_eda.ipynb`**: Exploratory Data Analysis (EDA) and data visualization steps to understand the data structure.
* 📓 **`Churn_Features_Final.ipynb`**: Data preprocessing, missing/outlier value management, and feature engineering to prepare the data for machine learning models.
* 📄 **`churn_features_final.csv`**: The cleaned and preprocessed dataset, ready for model training.
* 📓 **`Churn_Modeling.ipynb`**: The main modeling file where various machine learning classification algorithms are trained, tested, and their performance metrics are compared.

## ⚙️ Methodology
1. **Data Understanding & Cleaning:** Analyzed customer demographics and service usage data, performing necessary data cleaning operations.
2. **Feature Engineering:** Applied encoding to categorical variables and scaled the data for better machine learning algorithm performance.
3. **Modeling:** Built and evaluated classification models using the Scikit-learn library.
4. **Evaluation:** Evaluated models not only by Accuracy but also by metrics critical for imbalanced datasets, such as Precision, Recall, and F1-Score.

## 🚀 Installation & Usage
To run this project on your local machine, follow these steps:

1. Clone the repository:
   > `git clone https://github.com/uras-alkaya/Customer-Churn-Analysis.git`

2. Ensure you have the necessary libraries installed (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`). You can install them using pip:
   > `pip install pandas numpy scikit-learn matplotlib seaborn`

3. Open the project in Jupyter Notebook or VS Code and run the notebooks in the following order to review the results: 
   `churn_eda.ipynb` ➔ `Churn_Features_Final.ipynb` ➔ `Churn_Modeling.ipynb`

---
*Developed by: [Uras Alkaya](https://github.com/uras-alkaya)*