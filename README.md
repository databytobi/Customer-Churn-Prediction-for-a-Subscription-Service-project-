# Telco Customer Churn Prediction

This project focuses on building a predictive model to identify customers who are at risk of canceling their subscriptions. By analyzing customer data, the project aims to help telecommunication companies take proactive measures to retain at-risk customers.

---

## Overview

The project leverages machine learning techniques to predict customer churn. It involves data preprocessing, feature selection, model training, and evaluation using advanced tools and techniques. The following tasks are performed:
- Preprocessing data using scaling and encoding techniques
- Selecting important features for model training
- Training predictive models
- Evaluating models using various metrics

---

## Libraries and Tools Used

The project makes use of the following Python libraries:
- **Data Preprocessing**:
  - `MinMaxScaler`
  - `LabelEncoder`
  - `VarianceThreshold`
- **Data Splitting and Validation**:
  - `train_test_split`
  - `KFold`
  - `cross_val_score`
  - `cross_val_predict`
- **Feature Selection**:
  - `RFE`
- **Hyperparameter Tuning**:
  - `GridSearchCV`
- **Machine Learning Models**:
  - `LogisticRegression`
  - `RandomForestClassifier`
- **Evaluation Metrics**:
  - `accuracy_score`
  - `classification_report`
  - `confusion_matrix`
  - `r2_score`
  - `sqrt`

---

## Features

- **Data Preprocessing**: Scaling, encoding, and handling imbalanced datasets.
- **Feature Selection**: Identifying important features using techniques like `RFE` and `VarianceThreshold`.
- **Model Training**: Training classifiers including Logistic Regression and Random Forest.
- **Model Evaluation**: Evaluating performance using metrics like accuracy, classification report, and confusion matrix.
- **Hyperparameter Tuning**: Optimizing model parameters using `GridSearchCV`.

---

## Installation

### Prerequisites

Ensure you have Python installed along with the required libraries. Install the dependencies using the following command:

```bash
pip install -U scikit-learn pandas numpy matplotlib
```

---

## Usage

1. Clone the repository to your local system:
   ```bash
   git clone https://github.com/databytobi/telco-customer-churn.git
   ```
2. Run the script to preprocess data, train models, and evaluate performance:
   ```bash
   python main.py
   ```

---

## Project Structure

```
telco-customer-churn/
│
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks for exploration and visualization
├── src/                   # Source code
│   ├── data_processing.py # Data preprocessing scripts
│   ├── feature_selection.py # Feature selection scripts
│   ├── model_training.py  # Scripts for training models
│   └── evaluation.py      # Evaluation scripts
├── tests/                 # Unit tests
├── main.py                # Main script to run the project
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## Evaluation Metrics

The following metrics are used to evaluate the models:
- **Accuracy Score**: Measures the overall accuracy of the model.
- **Classification Report**: Provides precision, recall, and F1-score.
- **Confusion Matrix**: Shows the performance of the classification model.
- **R2 Score**: Measures the proportion of variance explained by the model.
- **Square Root Error**: Measures prediction error.

---

## Contributing

Contributions are welcome! If you have ideas for improvements or additional features, feel free to submit a pull request or open an issue.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Scikit-learn for providing tools for data preprocessing, model training, and evaluation.
- Pandas and NumPy for data manipulation.
- Matplotlib for data visualization.
