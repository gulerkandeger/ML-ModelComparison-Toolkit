# Classification Models Comparison

This repository compares the performance of various machine learning classification models based on their F1-scores. The project aims to provide insights into how different models perform on the same dataset, assisting in selecting the most suitable model for classification tasks.

## Project Overview

The notebook contains a comparison of several machine learning classification models applied to a dataset. The performance is evaluated based on the **F1-score** for each model, which is a common metric used in binary and multi-class classification tasks.

### Models Compared

The following models are compared in this project:

- **K-Nearest Neighbors (KNN)**
- **Decision Tree (DT)**
- **Random Forest (RF)**
- **Support Vector Machine (SVM)**
- **Gaussian Naive Bayes (GNB)**
- **Multilayer Perceptron (MLP)**
- **XGBoost Classifier (XGBC)**
- **Voting Classifier**

## Key Results

The F1-scores of the models are sorted in descending order to highlight the best-performing model.

| Model              | F1-Score  |
|--------------------|-----------|
| Voting Classifier   | 0.978     |
| K-Nearest Neighbors | 0.965     |
| Multilayer Perceptron| 0.953     |
| Random Forest       | 0.949     |
| Support Vector Machine | 0.941  |
| XGBoost Classifier  | 0.928     |
| Decision Tree       | 0.926     |
| Gaussian Naive Bayes| 0.857     |

The **Voting Classifier** achieved the highest F1-score, indicating it performs best on this dataset.

## Usage

To run this project locally:

1. Clone the repository:

   ```bash
   git clone <repository-url>

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

3. Run the notebook using Jupyter:

   ```bash
   jupyter notebook classifiaction_models_comparison.ipynb


## Dataset

The dataset used in this project is preprocessed to fit the classification models, ensuring proper feature scaling and data splitting.

## Dependencies

- Python 3.11
- Scikit-learn
- Pandas
- XGBoost
- Jupyter Notebook

## Conclusion

This project demonstrates the performance of various machine learning models on a classification task. The Voting Classifier emerged as the most accurate model in this comparison, but the choice of model may vary depending on the specific characteristics of other datasets.
