# Yokin-Yosoku (Credit Default Risk Prediction) 📊

A machine learning project to predict the probability of loan default using real credit data from the "Give Me Some Credit" Kaggle competition. This project implements classification algorithms to assess credit risk based on financial and demographic features.

> **Yokin-Yosoku** (預金予測) - Japanese for "Deposit Prediction" or "Credit Prediction"

## 📋 Project Overview

This project aims to help financial institutions make better lending decisions by predicting which borrowers are likely to experience financial distress in the next two years. The model analyzes various financial indicators and demographic information to calculate default risk probabilities.

## ✨ Key Features

- **Data Cleaning & EDA**: Comprehensive exploratory data analysis on real credit data with visualization of key risk factors
- **Feature Engineering**: Advanced feature engineering techniques for financial risk assessment
- **Multiple ML Models**: Implementation and comparison of various algorithms:
  - Logistic Regression
  - Random Forest
  - XGBoost
- **Model Evaluation**: Robust evaluation using metrics appropriate for credit risk (ROC-AUC, precision-recall)
- **Risk Probability Calibration**: Calibrated probability outputs for accurate risk assessment
- **Imbalanced Data Handling**: Techniques to address class imbalance in default prediction

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Scikit-learn** - Machine learning algorithms and evaluation
- **XGBoost** - Gradient boosting framework
- **Matplotlib/Seaborn** - Data visualization
- **NumPy** - Numerical computing

## 📁 Project Structure

```
credit-default-risk-prediction/
├── cs-training.csv          # Training dataset
├── cs-test.csv              # Test dataset
├── notebooks/               # Jupyter notebooks for analysis
├── src/                     # Source code
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── evaluation.py
├── models/                  # Saved model files
├── results/                 # Model outputs and predictions
├── requirements.txt         # Project dependencies
└── README.md
```

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.7+
pip or conda package manager
```

### Installation

1. Clone the repository
```bash
git clone https://github.com/Crimsn-moon/Yokin-Yosoku.git
cd Yokin-Yosoku
```

2. Install required packages
```bash
pip install -r requirements.txt
```

### Usage

1. **Data Preprocessing**
```python
python src/data_preprocessing.py
```

2. **Train Models**
```python
python src/model_training.py
```

3. **Generate Predictions**
```python
python src/evaluation.py
```

## 📊 Dataset

The project uses data from the "Give Me Some Credit" Kaggle competition, which includes:
- Demographic information
- Credit history
- Financial indicators
- Debt ratios
- Income levels
- Past payment behavior

## 📈 Model Performance

Model evaluation focuses on:
- **ROC-AUC Score**: Measuring discrimination ability
- **Precision-Recall**: Balancing false positives and false negatives
- **Calibration Plots**: Ensuring probability estimates are accurate
- **Confusion Matrix**: Understanding prediction patterns

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Crimsn-moon**
- GitHub: [@Crimsn-moon](https://github.com/Crimsn-moon)

## 🙏 Acknowledgments

- Kaggle for providing the "Give Me Some Credit" dataset
- The open-source community for the amazing tools and libraries

## 📧 Contact

For questions or feedback, please open an issue on GitHub.

---

⭐ If you find this project useful, please consider giving it a star!
