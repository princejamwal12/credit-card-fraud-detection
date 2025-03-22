# Credit Card Fraud Detection Project

## 📌 Overview
This project is a machine learning-based Credit Card Fraud Detection system. It uses a classification model to identify fraudulent transactions in a dataset, which is highly imbalanced.

## 📁 Project Structure
```
project/
│
├── creditcard.csv
├── credit_card_fraud_detection.ipynb
└── README.md
```

## 📊 Dataset
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Description:** The dataset contains transactions made by credit cards in September 2013 by European cardholders.
- **Features:** 31 total columns including `Time`, `V1-V28` (PCA features), `Amount`, and `Class`.

## 🔍 Key Highlights
- Data Preprocessing
- Handling Class Imbalance using `stratify` in `train_test_split`
- Train-Test split (80/20)
- Evaluation Metrics

## 🧠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib / Seaborn (optional for visualization)

## 🛠 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   ```
2. Navigate into the project folder:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook using Jupyter or VS Code.

## 📈 Results
Model training and evaluation show how well the classifier can detect rare fraud cases.

## 🙌 Author
Prince Jamwal

## 📬 Contact
For queries, reach out at: princejamwal2005@gmail.com

## 📃 License
This project is open-source under the MIT License.
