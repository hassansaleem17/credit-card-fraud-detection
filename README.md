# 💳 Credit Card Fraud Detection – Exploratory Data Analysis (EDA)

## 📌 Project Description

This project involves performing Exploratory Data Analysis (EDA) on a credit card transactions dataset to uncover hidden patterns associated with fraudulent behavior. By visualizing and analyzing both normal and fraudulent transactions, we aim to gain insights that can guide the development of effective machine learning models for fraud detection.

---

## 📊 Project Overview

- **Objective**: Explore and analyze the structure of fraudulent vs. legitimate credit card transactions.
- **Dataset**: Credit card transactions dataset with anonymized features (typically sourced from Kaggle).
- **File**: `fraud_detection.ipynb` – Jupyter Notebook containing all EDA steps, visualizations, and insights.

---

## 🧠 Key Analysis Performed

- Overview of class imbalance and distribution of fraudulent transactions.
- Time-based and amount-based analysis of transactions.
- Correlation matrix for anonymized features (V1 to V28).
- Comparative analysis between fraud and non-fraud groups.
- Boxplots, histograms, and pairwise comparisons for key features.

---

## 📁 Files Included

- `fraud_detection.ipynb`: Main Jupyter Notebook with complete EDA.
- *(Optional)* `creditcard.csv`: Raw dataset if included for local use.

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 📸 Visualizations Highlight

- Distribution of transaction amounts by class
- Class imbalance visualization (fraud vs. non-fraud)
- Correlation heatmaps
- Boxplots for key feature comparisons
- Histogram analysis of anonymized variables

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection-eda.git
   cd credit-card-fraud-detection-eda
````

2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook fraud_detection.ipynb
   ```

3. Ensure `creditcard.csv` is in the same directory if required.

---

## 📌 Next Steps

* Feature engineering and scaling
* Applying machine learning models (e.g., Logistic Regression, Random Forest, XGBoost)
* Evaluating with precision, recall, F1-score, and ROC AUC due to class imbalance

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
