# A Framework for Auditing Bias in AI-Based Hiring System

This project presents a bias auditing framework developed to evaluate the fairness and ethical compliance of AI-based hiring models. It leverages various classification algorithms and fairness metrics to detect and quantify potential biases in automated decision-making systems used in recruitment.

## 🧠 Overview

AI-powered hiring tools are increasingly used to automate and streamline recruitment processes. However, these systems may inadvertently perpetuate or even amplify societal biases. This project aims to identify and audit such biases in commonly used machine learning models using Python and Weka.

## 🚀 Features

- Implementation of classification algorithms: 
  - Decision Trees  
  - Logistic Regression  
  - Neural Networks  

- Bias auditing using fairness metrics:
  - **Disparate Impact**
  - **Equal Opportunity**
  - **Demographic Parity**

- Comparative analysis of fairness across different models and datasets.

## 🛠️ Technologies Used

- **Python** – Data preprocessing and fairness metric calculation
- **Weka** – Building and evaluating classification models
- **Pandas, NumPy, Matplotlib** – Data handling and visualization
- **Classification Algorithms** – For prediction-based bias assessment

## 📊 Datasets

We used synthetic and publicly available datasets simulating hiring scenarios with demographic attributes such as gender, race, and age.

> Note: Dataset sources and preparation steps are provided in the `data/` and `notebooks/` directories.

## ⚖️ Fairness Metrics Explained

- **Disparate Impact**: Compares favorable outcomes for unprivileged vs. privileged groups.
- **Equal Opportunity**: Measures if qualified candidates are equally likely to be hired regardless of group.
- **Demographic Parity**: Checks whether different groups receive positive outcomes at similar rates.

## 📈 Results

- Achieved ~85% accuracy across models on test data
- Disparate impact values ranged from 0.6 to 0.9, highlighting significant variation in model fairness
- Neural networks showed the highest performance but also the highest variability in fairness scores

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bias-auditing-ai-hiring.git
   cd bias-auditing-ai-hiring
