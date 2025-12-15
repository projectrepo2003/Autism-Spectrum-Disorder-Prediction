# Autism-Spectrum-Disorder-Prediction
This project focuses on predicting Autism Spectrum Disorder (ASD) using machine learning techniques. It involves analyzing a dataset, training classification models, and evaluating their performance to support early and accurate ASD identification.

<a href="https://colab.research.google.com/github/projectrepo2003/Autism-Spectrum-Disorder-Prediction/blob/main/AutismPrediction.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Key Features / Workflow
1. **Data Loading:** Reads dataset from CSV (example path: drive/MyDrive/train.csv).
2. **Exploratory Data Analysis (EDA):** Basic statistics, missing value checks, visualizations using seaborn and matplotlib.
3. **Preprocessing:** Encoding categorical variables, scaling or other transformations if needed, and handling missing values.
4. **Class Imbalance Handling:** Uses resampling techniques if dataset is imbalanced.
5. **Modeling:** Trains multiple classifiers (Decision Tree, Random Forest, XGBoost) and compares performance.
6. **Evaluation:** Uses accuracy_score, classification_report, and confusion_matrix to evaluate model performance.
7. **Model Persistence:** Trains final model and saves it with pickle for later inference.

## Requirements
Minimum required Python packages:
- pandas
- numpy
- scikit-learn
- xgboost
- imbalanced-learn
- seaborn
- matplotlib
- pickle (builtin)
You can install the packages with:

*!pip install pandas numpy scikit-learn xgboost imbalanced-learn seaborn matplotlib*

## How to run
1. Open AutismPrediction.ipynb in Jupyter Lab / Jupyter Notebook / Google Colab.
2. Update the dataset path if necessary (default in notebook: drive/MyDrive/train.csv).
3. Run the notebook cells in order. The notebook is organized to run step-by-step from imports → EDA → preprocessing → training → evaluation → save model.

#### At the end of the notebook, the trained model is used to make predictions on new/unseen data.
