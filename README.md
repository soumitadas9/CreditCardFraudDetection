# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It handles the challenge of imbalanced datasets and evaluates models for their performance in both balanced and imbalanced scenarios.

## Features
- Data preprocessing for imbalanced datasets.
- Use of advanced machine learning algorithms like XGBoost.
- Visualization of data distribution and model performance.
- Comprehensive evaluation metrics for fraud detection.

## Technologies Used
- **Python**: Core programming language.
- **Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `numpy`: Numerical computations.
  - `matplotlib` and `seaborn`: Data visualization.
  - `sklearn`: Machine learning utilities and metrics.
  - `imblearn`: Tools for handling imbalanced datasets.
  - `xgboost`: Gradient boosting for supervised learning.

## Key Functions
### 1. `evaluate_model`
General-purpose function to evaluate models.

### 2. `evaluate_balanced_data`
Evaluates model performance on balanced datasets.

### 3. `evaluate_model_imbalanced`
Evaluates model performance on imbalanced datasets.

## Dataset
The project uses a dataset with anonymized credit card transaction data, containing a highly imbalanced distribution of fraudulent and non-fraudulent transactions.

## Steps to Run
1. Clone this repository.
    ```bash
    git clone <repository-url>
    ```
2. Install the required dependencies.
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter Notebook and execute the cells.
    ```bash
    jupyter notebook CreditCardFraudDetection.ipynb
    ```

## Results
The project evaluates various models and compares their performance using metrics such as precision, recall, F1-score, and AUC-ROC.

## Contribution
Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
