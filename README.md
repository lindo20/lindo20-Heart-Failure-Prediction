
# Heart Failure Prediction

A machine learning project that predicts patient mortality (`DEATH_EVENT`) using clinical heart failure records.

## Dataset

299 patient records with 12 clinical features (age, ejection fraction, serum creatinine, platelets, etc.) plus the target `DEATH_EVENT`.

Source: [Kaggle -- Heart Failure Prediction Dataset](https://www.kaggle.com/code/karnikakapoor/heart-failure-prediction-ann/input)

## What This Project Does

- Cleans raw clinical data (fixes delimiters, missing values, formatting issues)
- Explores feature distributions and correlations with mortality
- Trains and compares two classification models: **SVM** and **Logistic Regression**
- Evaluates models using accuracy, precision, recall, and F1-score

## Tech Stack

Python · pandas · scikit-learn · matplotlib · seaborn · Google Colab

## How to Run

```bash
git clone https://github.com/yourusername/heart-failure-prediction.git
```
Open the notebook in Colab or Jupyter, update the dataset path, and run all cells.

## Files

- `heart_failure_prediction.ipynb` — main notebook
- `heart_failure_clinical_records_dataset.csv` — raw dataset

---
*For educational/portfolio purposes only — not for clinical use.*
