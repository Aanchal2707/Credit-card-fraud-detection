# Credit Card Fraud Detection

This repository contains a machine learning project aimed at detecting fraudulent transactions in credit card data. The project includes data preprocessing, visualization, feature extraction, model training, and evaluation steps. The model is designed to classify transactions as either legitimate or fraudulent.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Data Visualization](#data-visualization)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Credit card fraud detection is crucial for financial institutions to prevent losses and ensure customer trust. This project uses machine learning techniques to classify credit card transactions as fraudulent or legitimate.

## Features

- Data preprocessing: Cleaning and preparing the credit card data for modeling.
- Data visualization: Visualizing the distribution of features and the correlation between them.
- Model training: Implementing a logistic regression algorithm to train a fraud detection model.
- Model evaluation: Assessing the performance of the model using various metrics.

## Dataset

The dataset used in this project is the [Credit Card Fraud Detection Data](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, with 492 frauds out of 284,807 transactions.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/Aanchal2707/credit-card-fraud-detection.git
    cd credit-card-fraud-detection
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the dataset file (`creditcard.csv`) in the project directory. If not, download it from the provided link and place it there.

2. Run the script to execute data preprocessing, visualization, model training, and evaluation:
    ```bash
    python fraud_detection.py
    ```

## Data Visualization

The project includes various data visualization steps to understand the distribution of features and the correlation between them. Key visualizations include:

- Pie chart showing the distribution of legitimate and fraudulent transactions.
- Heatmap showing the correlation between different features.
- Histograms comparing the distribution of features for legitimate and fraudulent transactions.

## Model Training

The model training script (`fraud_detection.py`) performs the following steps:

1. Loads and preprocesses the data.
2. Visualizes the data to understand feature distributions and correlations.
3. Extracts features and splits the data into training and testing sets.
4. Trains a logistic regression model.
5. Evaluates the model using various metrics.

## Evaluation

The evaluation process involves assessing the model's performance using metrics such as accuracy, precision, recall, and F1-score. The results are printed to the console, along with a confusion matrix and classification report.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out if you have any questions or suggestions! Happy coding!

---

**Note:** Replace `Aanchal2707` with your actual GitHub username in the clone URL.
