# Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions in credit card datasets using machine learning techniques. The goal is to build an effective model that identifies fraudulent transactions with high accuracy while minimizing false positives and false negatives.

## Overview
Credit card fraud detection is a critical issue in the financial industry. This project uses a dataset containing transaction information to classify transactions as fraudulent or legitimate.

## Dataset
- **File**: `creditcard.csv`
- **Description**: The dataset contains credit card transactions made by European cardholders. It includes both legitimate and fraudulent transactions.
- **Features**:
  - **Time**: The seconds elapsed between each transaction and the first transaction.
  - **V1, V2, ..., V28**: Principal components obtained using PCA.
  - **Amount**: Transaction amount.
  - **Class**: Target variable (0 = legitimate, 1 = fraudulent).

## Notebook
- **File**: `ccfd.ipynb`
- **Description**: This Jupyter Notebook contains data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation steps for fraud detection.

## Requirements
To run this project, install the following dependencies:

```bash
pip install -r requirements.txt
```

### Key Libraries:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

## Project Structure
```plaintext
.
├── ccfd.ipynb         # Jupyter Notebook for the project
├── creditcard.csv     # Dataset
├── .gitattributes     # Git configuration (if applicable)
└── README.md          # Project documentation
```

## How to Use
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook ccfd.ipynb
   ```
4. Run the cells sequentially to perform data analysis, model training, and evaluation.

## Results
The project evaluates various machine learning models, such as Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting, for detecting fraudulent transactions. Performance metrics include:
- Precision
- Recall
- F1-Score
- Accuracy
- ROC-AUC Curve

## Challenges
- Imbalanced Dataset: The dataset has a highly skewed class distribution (legitimate vs. fraudulent transactions).
- Model Optimization: Selecting the best model and tuning hyperparameters for optimal performance.

## Future Enhancements
- Implementing deep learning models for better fraud detection.
- Real-time fraud detection using streaming data.
- Integrating the solution with a web application or API.

## Contribution
Contributions are welcome! Feel free to submit issues or pull requests.

## License

---

### Acknowledgments
- The dataset is sourced from [Kaggle's Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).

