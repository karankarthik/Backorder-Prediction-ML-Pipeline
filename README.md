# Backorder-Prediction-ML-Pipeline
Machine learning pipeline for predicting product backorders using anomaly detection, feature selection, and logistic regression. Includes detailed notebooks on preprocessing, model development, and evaluation.

# Backorder Prediction ML Pipeline

This repository contains the complete machine learning pipeline for predicting backorders using anomaly detection, feature selection, and logistic regression. The project is divided into three main parts: Preprocessing, Model Development, and Evaluation.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Notebooks](#notebooks)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The goal of this project is to predict product backorders using historical sales data. The pipeline involves data preprocessing, anomaly detection using Local Outlier Factor, feature selection, and logistic regression modeling with hyperparameter tuning.

## Dataset
The dataset used for this project includes historical sales data, product features, and backorder status. The dataset is preprocessed to handle missing values, outliers, and irrelevant features.

## Notebooks
1. **Part 1: Preprocessing** (`FP-Part1-Preprocessing.ipynb`)
   - Data cleaning and preprocessing
   - Handling missing values and outliers
   - Feature engineering and selection

2. **Part 2: Model Development** (`FP-Part2-Model-Development.ipynb`)
   - Anomaly detection using Local Outlier Factor
   - Logistic regression model development
   - Hyperparameter tuning using GridSearchCV

3. **Part 3: Evaluation** (`FP-Part3-Evaluation.ipynb`)
   - Model evaluation and performance metrics
   - Confusion matrix and classification report
   - Cross-validation results

## Installation
To run the notebooks, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Backorder-Prediction-ML-Pipeline.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Backorder-Prediction-ML-Pipeline
    ```

3. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
Open the Jupyter notebooks in your preferred environment (Jupyter Notebook, JupyterLab, VSCode, etc.) and run the cells sequentially to reproduce the results.

## Results
The final model achieved a cross-validation score of 0.78 and a training accuracy of 0.78. The classification report and confusion matrix for the training data are as follows:

- **Precision**: 0.89 for class 0, 0.72 for class 1
- **Overall Accuracy**: 0.78
- **Confusion Matrix**: [[3911, 2592], [481, 6679]]

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
