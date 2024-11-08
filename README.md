# California Housing Price Prediction

This project leverages the California Housing dataset to predict housing prices based on various features such as median income, occupancy, and geographic attributes. The notebook uses TensorFlow and Keras to build and evaluate a neural network model for regression tasks.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Notebook Structure](#notebook-structure)
- [Results](#results)
- [License](#license)

## Introduction
The aim of this project is to build a predictive model for California housing prices using machine learning techniques. This notebook walks through data preprocessing, normalization, model building, and evaluation steps for effective price prediction.

## Prerequisites
Ensure the following software is installed:
- Python 3.6+
- Jupyter Notebook
- TensorFlow and Keras
- Other dependencies (listed in `requirements.txt`)

## Setup and Installation
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd california-housing-price-prediction
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook california_housing.ipynb
   ```

## Usage
To use this notebook:
1. Open `california_housing.ipynb` in Jupyter Notebook.
2. Execute each cell in sequence to:
   - Load and preprocess the dataset.
   - Split the dataset into training, validation, and test sets.
   - Normalize the data.
   - Train the model and assess its performance.

## Notebook Structure
1. **Data Loading**: Imports the California Housing dataset from Scikit-Learn.
2. **Data Splitting**: Divides the data into training, validation, and test sets.
3. **Data Normalization**: Scales the data using `StandardScaler` to improve training performance.
4. **Model Training**: Builds a neural network with TensorFlow and Keras, trains it on the dataset, and validates it.
5. **Evaluation**: Analyzes model accuracy and performance on the test set.

## Results
The model’s performance metrics and error rates are evaluated to provide insights into its accuracy in predicting housing prices.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

