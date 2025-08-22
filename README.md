# Loan Sanction amount(USD) Prediction using Linear Regression

## Overview
This project develops a machine learning model to predict loan sanction amounts for financial institutions using linear regression. The model analyzes borrower demographics and property characteristics to estimate appropriate loan amounts, helping automate and standardize the lending process.

## Dataset
- **Source**: [Add your dataset source here]
- **Size**: 47251 records, 8 features
- **Target Variable**: Loan transaction amount
- **Features**:
  - Age
  - Income (USD)
  - Property Age
  - Property Price
  - Loan Sanction Amount (USD) <-- target feature
  - [Add other relevant features]

## Requirements
```
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
```

## Installation
1. Clone this repository:
```bash
git clone
cd house-loan-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Project Structure
```
├── Data/
│   └── house_loan.csv
├── Python Notebooks/
│   └── House_loan_prediction.ipynb
├── README.md
└── requirements.txt
```

## Methodology

### 1. Data Exploration
- Exploratory Data Analysis (EDA)
- Missing value analysis
- Distribution analysis of features
- Correlation analysis

### 2. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling/normalization
- Outlier detection and treatment

### 3. Model Development
- Train-test split
- Linear regression implementation
- Model training and validation

### 4. Model Evaluation
- Performance metrics:
  - Mean Absolute Error (MAE)
- Feature importance analysis

## Results
- **MAE Score (mean_absolute_error)**: 1956.843132470082

## Usage
1. Open the Jupyter notebook:
```bash
jupyter notebook notebooks/House_loan_predictions.ipynb
```

2. Run all cells to reproduce the analysis
3. Test model on new dataset

## Future Improvements
- [ ] Implement ensemble methods (Random Forest, Gradient Boosting)
- [ ] Feature engineering and selection
- [ ] Handle class imbalance if present
- [ ] Deploy model using Flask/FastAPI

## Contact
- **Author**: Caelum
- **Email**: thaianhwastaken@gmail.com
- **LinkedIn**:www.linkedin.com/in/thái-anh-nguyễn-dương-4a128232b
- **GitHub**:https://github.com/Caelum-hash
