# Naive Bayes Classifier on Social Network Ads

This project implements a Naive Bayes classifier to predict whether a user purchases a product based on their age and estimated salary. The dataset used is `Social_Network_Ads.csv`.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)
- [License](#license)

## Overview

The goal is to classify users into two categories:
- Purchased (1)
- Not Purchased (0)

This is achieved using a **Gaussian Naive Bayes** model from scikit-learn. The workflow includes:
- Data preprocessing
- Train-test split
- Feature scaling
- Model training
- Prediction
- Evaluation (confusion matrix & accuracy)
- Decision boundary visualization

## Dataset

The dataset `Social_Network_Ads.csv` should contain at least the following columns:
- Age
- Estimated Salary
- Purchased (target variable)

## Installation

1. Clone this repository.
2. Install the required Python packages:

```bash
pip install numpy pandas matplotlib scikit-learn




