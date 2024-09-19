# Description
This project aims to classify loan applicants into different risk categories using machine learning techniques. By analyzing various features of loan applicants, we can predict their likelihood of defaulting on a loan, enabling financial institutions to make informed lending decisions.

## Features

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Exploratory Data Analysis**: Visualizing relationships between features and the target variable.
- **Model Training**: Implementing various machine learning algorithms for classification.
- **Evaluation Metrics**: Assessing model performance using accuracy, precision, recall, and F1-score.

## Dataset

The dataset used in this project contains information on loan applicants, including features such as:

- Age
- Gender
- Marital Status
- Employment Status
- Annual Income
- Credit Score
- Loan Amount
- Loan Purpose

For more details, refer to the `data/` directory.

## Installation

To run this project, ensure you have Python installed. Then, clone the repository and install the required packages:

```bash
git clone https://github.com/satish2419/Classifying-Loan-Applicant-Risk-Segmentation.git
cd Classifying-Loan-Applicant-Risk-Segmentation
pip install -r requirements.txt

Usage
You can run the main script to train the model and make predictions:
python main.py

Configuration
You can modify parameters in config.py to adjust model settings, such as:
Number of neighbors (K)
Distance metric (Euclidean, Manhattan, etc.)
Test/train split ratio

KNN Model
The K-Nearest Neighbors (KNN) algorithm is a simple yet effective classification technique that works by finding the K closest data points in the training set to the new data point. The class label is determined based on the majority class among those neighbors.

Key Steps:
Data Normalization: KNN is sensitive to feature scaling; hence, all numerical features are normalized.
Distance Calculation: The model computes distances using the chosen metric (e.g., Euclidean).
Prediction: For each applicant, KNN identifies the K nearest neighbors and predicts the risk category.

Results
After running the model, The training_score is 67.5%, Testing Score is 64.5, Accuracy Score is 64.53%.
