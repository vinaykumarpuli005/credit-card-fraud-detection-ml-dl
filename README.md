# Credit Card Fraud Detection Using Machine Learning and Deep Learning

## Project Overview
This project detects fraudulent credit card transactions using Machine Learning and Deep Learning models. The dataset is highly imbalanced, so the project focuses on identifying fraud transactions using metrics like Recall, F1-Score, and ROC-AUC instead of only accuracy.

## Dataset
Dataset: Credit Card Fraud Detection Dataset  
Source: Kaggle  
Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset contains credit card transactions labeled as:
- `0` - Normal transaction
- `1` - Fraud transaction

Note: The dataset file `creditcard.csv` is not uploaded because of file size. It can be downloaded from the Kaggle link above.

## Business Problem
Fraud transactions are rare but costly. The goal is to build a model that can correctly identify suspicious transactions and reduce the risk of financial loss.

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
10. Saved the trained model and scaler

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
| Logistic Regression | Add value | Add value | Add value | Add value |
| Random Forest | Add value | Add value | Add value | Add value |
| Neural Network | Add value | Add value | Add value | Add value |

## Files Included
- `credit_card_fraud_detection.ipynb` - complete project notebook
- `requirements.txt` - required Python libraries
- `README.md` - project documentation

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
- Handling imbalanced data
- Machine Learning classification
- Deep Learning model building
- Model evaluation
- Fraud detection analysis
- Python programming

## Conclusion
This project shows how Machine Learning and Deep Learning can be used to detect fraudulent credit card transactions. Since the dataset is highly imbalanced, Recall, F1-Score, and ROC-AUC were used as important evaluation metrics.
