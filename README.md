# Solubility Prediction using Linear Regression

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Dependencies](#dependencies)
4. [Getting Started](#getting-started)
5. [Usage](#usage)
6. [Results](#results)
7. [Contributing](#contributing)


---

## Introduction

This project aims to predict the solubility of organic compounds in water, measured as LogS, using a dataset of known molecules and their calculated molecular descriptors. Linear Regression is used as the machine learning algorithm for the prediction task. Evaluation metrics like Mean Squared Error (MSE) and \( R^2 \) score are used to assess the model's performance.

---

## Features

- Importing dataset from a CSV file
- Data preprocessing
- Feature extraction
- Data split into training and testing sets
- Model building using Linear Regression
- Model evaluation using MSE and \( R^2 \) score
- Visualization of predicted vs actual values

---

## Dependencies

- Python 3.8 or higher
- pandas
- scikit-learn
- matplotlib
- numpy

---

## Getting Started

Clone the repository:
\`\`\`
git clone https://github.com/paulojose177/Solubility-ML-LinearRegression.git
\`\`\`

Install the dependencies:
\`\`\`
pip install -r requirements.txt
\`\`\`

---

## Usage

Open the Jupyter Notebook file:
\`\`\`
 ML Algorithm Solubility.ipynb
\`\`\`

To execute the code, you have to run each of the respective Jupyter Notebook cells, and you will see the model's training and testing metrics printed on the console. Additionally, a plot will be generated to visualize the model's predictions against the actual values.

---

## Results

Here are some preliminary results based on the Linear Regression model:

- **Training MSE**: 1.007536295109369
- **Training \( R^2 \)**: 0.764505177466339
- **Test MSE**: 1.0206953660861033
- **Test \( R^2 \)**: 0.7891616188563282

---

## Contributing

If you would like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

---
