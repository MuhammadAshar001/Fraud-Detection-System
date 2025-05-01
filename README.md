# Fraud Detection System — Task 3

This project implements a **fraud detection system** using a labeled dataset of credit card transactions to classify them as either **legitimate** or **fraudulent** using machine learning algorithms.

---

## Features

- Handles **imbalanced datasets** using SMOTE and undersampling
- Trains ML model: **Random Forest** 
- Evaluation based on **precision**, **recall**, **F1-score**, and **confusion matrix**
- Interactive **command-line testing interface** to manually test transactions

---

## Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

---

## Final Results
```bash 
Classification Report:
                precision    recall  f1-score   support

   Not Fraud       1.00      1.00      1.00     85295
       Fraud       0.88      0.80      0.84       148

    accuracy                           1.00     85443
   macro avg       0.94      0.90      0.92     85443
weighted avg       1.00      1.00      1.00     85443

```
Model Used: Random Forest
Performance: High accuracy, with strong results even for the minority fraud class

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection.git
   cd fraud-detection
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or Python script:
   - For Jupyter: Open `task3.ipynb` and run all cells.

---

## Input

- Dataset: `creditcard.csv` (features V1–V28, Time, Amount, and Class)
- Manual transaction input through command-line interface for prediction

---

## Output

- Evaluation metrics on the test set
- Prediction for manual input (❗ Fraud / ✅ Legit)

---

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your suggested improvements.

---

## License

This project is open-source and available under the **MIT License**.

---

> Designed with accuracy and practicality in mind — ideal for real-time fraud detection systems.

