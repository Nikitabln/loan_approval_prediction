# Loan Approval Prediction: Modular ML Pipeline

This project demonstrates a robust, modular pipeline for loan approval prediction using advanced machine learning models, feature engineering, and ensemble techniques. The workflow includes:

- Exploratory Data Analysis (EDA)
- Baseline models Linear Regression, 
- Advanced models: CatBoost
- Out-of-fold stacking and ensemble methods
- Optuna hyperparameter tuning
- Submission file generation

## Project Structure

- `loan_approval_pred.ipynb` — Main Jupyter notebook with the full pipeline
- `data/` — Folder containing `train.csv`, `test.csv`, and `sample_submission.csv`
- `results/` — Folder for saving submission files

## Getting Started

### 1. Clone the repository and install requirements

```sh
pip install -r requirements.txt
```

### 2. Data

Place your data files in the `data/` directory:
- `train.csv`
- `test.csv`
- `sample_submission.csv`

### 3. Run the Notebook

Open `loan_approval_pred.ipynb` in Jupyter or VS Code and run the cells step by step.

## Requirements

Main libraries used:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- catboost
- optuna
- tqdm

See `requirements.txt` for details.

## Output

Submission files are saved in the `results/` directory.

---
Public Score: 0.96939

**Author:**  
Nikita

**License:**  
MIT
