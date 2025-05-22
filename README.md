# Mahine-Learning-Project
# Customer Churn Prediction

## Objective
Build a machine learning model to predict customer churn, enabling proactive retention strategies.

## Dataset
- Source: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- 7,043 rows × 21 columns
- Target variable: `Churn`

## Data Preprocessing
- Cleaned missing/incorrect data
- Encoded categorical features
- Scaled numerical features
- Split data: 80% train / 20% test

## Exploratory Data Analysis (EDA)
- Analyzed churn distribution by contract, tenure, internet service, and monthly charges.
- Visualized patterns using plots.

## Model Training & Evaluation

| Model                 | Accuracy | Churn Recall | Churn Precision | F1-score |
|-----------------------|----------|--------------|-----------------|----------|
| Logistic Regression   | ...      | ...          | ...             | ...      |
| Decision Tree (Tuned) | ...      | ...          | ...             | ...      |
| Random Forest         | ...      | ...          | ...             | ...      |
| **Gradient Boosting** | **77.5%**| **65%**      | 57%             | **61%**  |

*Final model used Gradient Boosting with threshold tuning for improved recall.*

## Key Learnings
- Threshold tuning impacts precision-recall tradeoff.
- Recall is critical in churn prediction.
- Practical experience with feature engineering, model tuning, and evaluation.

## Tools
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## How to Run
1. Clone the repo
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook `churn_prediction.ipynb`

---

Feel free to reach out or open an issue for questions!
