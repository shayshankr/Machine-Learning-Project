# Machine Learning Project: Smart Fraud Detection System

This project applies machine learning techniques to detect fraudulent bank transactions using a real-world banking dataset.

## Project Overview

- **Dataset:** Bank transaction data with transaction, demographic, and device information (2,512 records, 16 features)
- **Goal:** Classify transactions as fraudulent or genuine using multiple ML models and an ensemble approach
- **Techniques:** SMOTE for class imbalance, Label Encoding, Log Transformation, XGBoost, Random Forest, MLP (Neural Network), Ensemble Soft Voting, ROC Analysis

## Results

| Model | Accuracy | ROC AUC |
|---|---|---|
| XGBoost | ~0.77 | ~0.85 |
| Random Forest | ~0.77 | ~0.85 |
| MLP (Neural Network) | ~0.77 | ~0.85 |
| **Ensemble (Soft Voting)** | **0.77** | **0.85** |

## Notebook Structure

1. Importing Necessary Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing & Feature Engineering
5. Train-Test Split and SMOTE
6. Model Training: Random Forest & XGBoost
7. Deep Learning Model: MLP
8. Model Evaluation: Metrics & ROC
9. Ensemble Model: Soft Voting
10. Error Analysis
11. Learning Curve: Random Forest
12. Timing Analysis

## How to Run

```bash
git clone https://github.com/shayshankr/Machine-Learning-Project.git
cd Machine-Learning-Project
pip install -r requirements.txt
jupyter notebook Machine_learning_Project.ipynb
```

Run each cell sequentially from top to bottom. The dataset `bank_transactions_data_2.csv` is included in the repo.

## Requirements

- Python 3.10+
- See `requirements.txt` for all dependencies (no TensorFlow required)

## File Structure

```
├── Machine_learning_Project.ipynb              # Main analysis notebook
├── bank_transactions_data_2.csv                # Dataset
├── requirements.txt                            # Python dependencies
├── Machine Learning Project Report.pdf         # Full written report
├── Fraud_Detection_Project_Shayshank_Presentation.pptx  # Slide deck
└── Smart Fraud Detection System Presentation.mp4         # Video presentation
```

## Author

- **Name:** Shayshank Rathore
- **Student ID:** x23348186
- **Email:** x23348186@student.ncirl.ie
