# Spark-Analysis-on-Wine-quality-Dataset-
A machine learning project that predicts wine quality based on various physicochemical properties using a dataset of red wine samples. This project applies data preprocessing, exploratory data analysis (EDA), and multiple ML algorithms to build accurate predictive models.

##  Project Overview

This notebook walks through the following stages:
* Loading and cleaning the dataset
* Exploratory data analysis (EDA)
* Correlation heatmaps and feature importance
* Model training and evaluation (Logistic Regression, Decision Tree, Random Forest, etc.)
* Final model selection based on accuracy, precision, and recall

##  Dataset
The dataset used is the **Red Wine Quality dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).

Each sample contains 11 numerical features and a quality score (integer from 0 to 10) rated by wine tasters.

## Features

* **Fixed acidity**
* **Volatile acidity**
* **Citric acid**
* **Residual sugar**
* **Chlorides**
* **Free sulfur dioxide**
* **Total sulfur dioxide**
* **Density**
* **pH**
* **Sulphates**
* **Alcohol**
* **Quality** (target variable)

## Technologies & Libraries

* Python
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/wine-quality-analyzer.git
   cd wine-quality-analyzer
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook Wine_Quality_Analyzer.ipynb
   ```

## Model Performance

The notebook compares multiple classification models and outputs accuracy, confusion matrices, and classification reports. The Random Forest classifier typically achieves the best performance on this dataset.

## Results Snapshot

* Best model: **Random Forest Classifier**
* Accuracy: \~87% (depending on train/test split)
* Key feature: **Alcohol** was found to be the most influential in predicting wine quality.

## TODOs

* [ ] Tune hyperparameters using GridSearchCV
* [ ] Export the best model with `joblib` or `pickle`
* [ ] Create a web app interface (e.g., with Streamlit or Flask)
