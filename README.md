# Bank Churn Prediction Algorithm

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

Welcome to the **Bank Churn Prediction Algorithm** project! This repository contains all the necessary scripts and files to build and deploy a machine learning model for predicting customer churn in a bank.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Notebooks](#notebooks)
- [Scripts Overview](#scripts-overview)
- [Model and Preprocessor](#model-and-preprocessor)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer churn refers to the loss of clients or customers. For banks, understanding and predicting churn is crucial to developing strategies to retain customers. This project involves various stages of data processing, feature engineering, and model training using machine learning algorithms to predict customer churn accurately.

## Project Structure

The project is organized as follows:

- `app.py`: Main application script
- `data_ingestion.py`: Script for data ingestion
- `data_transformation.py`: Script for data transformation
- `model_trainer.py`: Script for training models
- `predict_pipeline.py`: Pipeline for making predictions
- `utils.py`: Utility functions
- `exception.py`: Custom exception handling
- `logger.py`: Logging setup
- `model.pkl`: Trained machine learning model
- `preprocessor.pkl`: Data preprocessor object
- `requirements.txt`: Python dependencies
- `setup.py`: Setup file for packaging
- `.gitignore`: Git ignore file
- `README.md`: Project README file

## Installation

To get started with the project, you need to clone the repository and install the necessary Python packages. Follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/jan-1995/Bank-Churn-Pediction-Algorithm-.git
    cd Bank-Churn-Pediction-Algorithm-
    ```

2. **Install the dependencies:**

    Install the required Python packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the project, use the following command:

```bash
python app.py
