# Dataset Details

## Dataset Name
Credit Card Fraud Detection Dataset

## Source
Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Dataset Description
This dataset contains credit card transactions made by European cardholders. The objective is to classify each transaction as normal or fraudulent.

## Target Column

| Column | Description |
|---|---|
| `Class` | Target variable |
| `0` | Normal transaction |
| `1` | Fraud transaction |

## Main Columns

| Column | Description |
|---|---|
| `Time` | Seconds elapsed between transactions |
| `V1` to `V28` | PCA-transformed transaction features |
| `Amount` | Transaction amount |
| `Class` | Fraud label |

## Dataset Size
- Rows: 284,807
- Columns: 31
- Fraud transactions: 492
- Normal transactions: 284,315

## Important Note
The dataset is highly imbalanced. Fraud transactions are very rare compared to normal transactions. Because of this, Accuracy is not the best evaluation metric. Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrix are more useful.

## Why The Dataset Is Not Uploaded
The raw file `creditcard.csv` is not uploaded to GitHub because it is large. It should be downloaded directly from Kaggle.

## How To Use The Dataset
1. Download the dataset from Kaggle.
2. Extract the file.
3. Place `creditcard.csv` in the project root folder.
4. Run the notebook `credit_card_fraud_detection.ipynb`.

Expected local structure:

```text
credit-card-fraud-detection-ml-dl/
|
|-- creditcard.csv
|-- credit_card_fraud_detection.ipynb
|-- README.md
|-- DATASET.md
|-- requirements.txt
```

## Data Preparation Used
- Checked missing values
- Checked class imbalance
- Scaled numerical columns
- Split data into train and test sets
- Applied SMOTE only on training data
- Trained Machine Learning and Deep Learning models
