# week_8_and_9
week_8_and_9
# Fraud Detection Pipeline

This project implements a fraud detection pipeline using machine learning and deep learning techniques. The pipeline includes data preprocessing, feature engineering, model training, explainability, and deployment.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model Training](#model-training)
6. [Explainability](#explainability)
7. [Deployment](#deployment)
8. [Contributors](#contributors)

## Project Overview
The objective of this project is to detect fraudulent transactions using supervised machine learning models and deep learning architectures such as CNNs and LSTMs. Additionally, explainability tools like SHAP and LIME are used to interpret model decisions.

## Dataset Description
- `Fraud_Data.csv`: Contains e-commerce transaction details labeled as fraudulent or non-fraudulent.
- `IpAddress_to_Country.csv`: Maps IP addresses to countries.
- `creditcard.csv`: Contains anonymized credit card transactions.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/fraud-detection.git
   cd fraud-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
### Data Preprocessing & Feature Engineering
Run the script to clean and preprocess the data:
```sh
python fraud_detection_pipeline.py
```

### Model Training
Train various models including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, CNN, and LSTM.
```sh
python model_training.py
```

### Explainability
Run SHAP and LIME for model interpretation:
```sh
python explainability.py
```

## Deployment
1. Set up the Flask API:
   ```sh
   python serve_model.py
   ```
2. Run with Docker:
   ```sh
   docker build -t fraud-detection-model .
   docker run -p 5000:5000 fraud-detection-model
   ```

## Contributors
Bethelhem Teka


