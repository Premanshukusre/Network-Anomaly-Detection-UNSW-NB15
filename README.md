# Network Anomaly Detection using UNSW-NB15

This project is part of **Machine Learning TAE-1** (Project Based Learning).

## Objective

The objective of this project is to detect network anomalies using multiple machine learning algorithms on the UNSW-NB15 dataset.

## Introduction

This project focuses on identifying malicious network activities using supervised machine learning techniques. It compares multiple models to determine the most effective approach for intrusion detection.

## Dataset

The dataset used is **UNSW-NB15** [[1](#references), [2](#references)] (also available on [Kaggle](https://www.kaggle.com/)).

It contains modern network traffic with both normal and attack data.

### Target Variable

- **0** → Normal Traffic
- **1** → Attack / Anomaly

## Models Implemented

- Decision Tree
- Random Forest
- XGBoost
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Support Vector Machine (SVM)
- Naive Bayes

## Project Structure

```
Network-Anomaly-Detection-UNSW-NB15/
├── README.md
├── datasets/
├── models/
├── logs/
└── notebooks/
```

## Installation

### Prerequisites

- Python 3.7+
- pip

### Clone the Repository

```bash
git clone https://github.com/Premanshukusre/Network-Anomaly-Detection-UNSW-NB15.git
cd Network-Anomaly-Detection-UNSW-NB15
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

### Download Dataset

Place dataset files inside the `datasets/` folder or upload in Google Colab.

## Usage

1. Open the `.ipynb` files in Google Colab or Jupyter Notebook
2. Execute all cells step-by-step
3. Models will train and display results

## Results

### Accuracy Comparison

| Model | Accuracy |
|-------|----------|
| Decision Tree | 99.96% |
| Random Forest | 99.92% |
| XGBoost | 97.76% |
| KNN | 97.61% |
| Logistic Regression | 94.98% |
| SVM | 94.77% |
| Naive Bayes | 71.09% |

## Best Model

**Random Forest** performed best due to its ensemble learning capability and stability.

## Model Insights

- **Decision Tree**: High accuracy but prone to overfitting
- **Random Forest**: Best overall performance
- **XGBoost**: Balanced and reliable
- **SVM and Logistic Regression**: Moderate performance
- **KNN**: Good accuracy but slower prediction
- **Naive Bayes**: Lowest performance due to feature independence assumption

## Limitations

- Possible overfitting in Decision Tree
- Limited hyperparameter tuning
- Higher computation time for some models

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Highlights

- Implemented multiple machine learning models
- Compared performance using accuracy, precision, recall, and F1-score
- Applied preprocessing and feature scaling where required
- Maintained structured workflow using GitHub

## Future Scope

- Apply deep learning models (ANN, CNN)
- Perform hyperparameter tuning
- Improve feature engineering
- Develop real-time intrusion detection system
- Use Explainable AI techniques

## References

[1] [UNSW-NB15 Dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
[2] Additional dataset resources

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is open source and available under the MIT License.