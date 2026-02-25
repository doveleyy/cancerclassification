# ML Model Project: SVM, XGBoost, and TabNet

This project implements three distinct machine learning models—SVM, XGBoost, and TabNet—designed to run independently for data analysis and classification tasks.

---

## Installation

To set up the environment, you can install the required dependencies using the command found in `svmmodel.py`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost torch pytorch-tabnet
```

Alternatively, you can install the specific versions listed in the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

---

## Execution Guide

The project consists of three main Jupyter Notebook files that should be executed independently:

1.  **SVM Model:** Run `svmmodel.ipynb`
2.  **XGBoost Model:** Run `xgboostmodel.ipynb`
3.  **TabNet Model:** Run `tabnetmodel.ipynb`

---

## Important Performance Notes

* **GridSearchCV:** Both the **XGBoost** and **SVM** models utilize `GridSearchCV` for hyperparameter optimization.
* **Execution Time:** Please allow approximately **10 minutes** for each of these models to finish running.
* **Hardware Recommendation:** Due to the processing requirements of the grid search, it is recommended to run these scripts on a good PC.

---

## Core Dependencies
The project relies on the following key libraries:
* **scikit-learn** (1.6.1)
* **xgboost** (3.0.0)
* **pytorch-tabnet** (4.1.0)
* **torch** (2.6.0)
* **pandas** (2.2.3)
* **numpy** (2.2.4)