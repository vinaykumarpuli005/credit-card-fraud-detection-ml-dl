# Credit Card Fraud Detection Using Machine Learning and Deep Learning

## Project Overview
This project detects fraudulent credit card transactions using Machine Learning and Deep Learning models. The dataset is highly imbalanced, so the project focuses on identifying fraud transactions using Recall, F1-Score, ROC-AUC, and confusion matrix analysis instead of only accuracy.

## Business Problem
Fraud transactions are rare but costly. The goal is to build a model that can correctly identify suspicious transactions and help reduce financial risk.

## Dataset
Dataset: Credit Card Fraud Detection Dataset  
Source: Kaggle  
Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Target column:
- `0` - Normal transaction
- `1` - Fraud transaction

Note: The dataset file `creditcard.csv` is not uploaded because of file size. Download it from Kaggle and place it in the project folder before running the notebook. More details are available in `DATASET.md`.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- TensorFlow/Keras
- Joblib

## Project Workflow
1. Imported the dataset
2. Checked data shape, data types, missing values, and class distribution
3. Performed exploratory data analysis
4. Scaled numerical features
5. Split data into training and testing sets
6. Applied SMOTE to handle class imbalance
7. Trained Machine Learning and Deep Learning models
8. Evaluated models using classification metrics
9. Compared model performance
10. Saved the trained model and scaler locally

## Models Used
- Logistic Regression
- Random Forest Classifier
- Neural Network

## Evaluation Metrics
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curve

## Model Comparison

| Model | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.0580 | 0.9184 | 0.1092 | 0.9699 |
| Random Forest | 0.8454 | 0.8367 | 0.8410 | 0.9731 |
| Neural Network | 0.6148 | 0.8469 | 0.7124 | 0.9784 |

## Key Insights
- The dataset is highly imbalanced, so accuracy alone is not a reliable metric.
- Logistic Regression achieved high recall but low precision, meaning it detected many fraud cases but also produced many false positives.
- Random Forest provided the strongest balance between Precision, Recall, and F1-Score.
- Neural Network achieved the highest ROC-AUC, showing strong overall separation between fraud and normal transactions.

## Repository Structure

```text
credit-card-fraud-detection-ml-dl/
|
|-- README.md
|-- DATASET.md
|-- requirements.txt
|-- .gitignore
|-- credit_card_fraud_detection.ipynb
|-- screenshots/
|   |-- README.md
```

## Files Included
- `credit_card_fraud_detection.ipynb` - complete project notebook
- `requirements.txt` - required Python libraries
- `DATASET.md` - dataset source, columns, and usage details
- `.gitignore` - prevents large dataset/model files from being uploaded
- `screenshots/README.md` - guide for adding project chart screenshots

## How To Run
1. Download the dataset from Kaggle.
2. Place `creditcard.csv` in the project folder.
3. Install required libraries:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook credit_card_fraud_detection.ipynb
```

5. Run all cells from top to bottom.

## Skills Demonstrated
- Data preprocessing
- Exploratory data analysis
- Handling imbalanced data using SMOTE
- Machine Learning classification
- Deep Learning model building
- Model evaluation
- Fraud detection analysis
- Python programming

## Conclusion
This project shows how Machine Learning and Deep Learning can be used to detect fraudulent credit card transactions. Since the dataset is highly imbalanced, Recall, F1-Score, ROC-AUC, and confusion matrix analysis were used as important evaluation metrics. Random Forest gave the best balanced performance, while the Neural Network achieved the highest ROC-AUC.
