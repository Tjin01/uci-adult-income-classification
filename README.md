## 📌 Project Overview
This project predicts whether an individual's annual income exceeds $50K based on census data.

## 📂 Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)
- 32,560 rows, 14 features (categorical + numerical)

## 🛠 Methods
- Data cleaning & preprocessing with `scikit-learn` pipelines
- Feature engineering: Combined `capital-gain` and `capital-loss` into net capital gain
- Models: Logistic Regression, Random Forest
- Hyperparameter tuning with `GridSearchCV`

## 📊 Results
- **Random Forest**: Precision (high income) = 77%
- **Logistic Regression**: Precision (high income) = 74%
- Chose Precision due to class imbalance (75% ≤50K vs. 25% >50K)


## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook uci_adult_income.ipynb

**Live Version on Kaggle:** Click Here(https://www.kaggle.com/code/tjinnie/uci-adult-income-dataset-census-income/254347204)
