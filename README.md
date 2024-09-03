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

The project is organized as follows:

```bash
├── notebooks
│   ├── 1. EDA STUDENT PERFORMANCE.ipynb
│   └── 2. MODEL TRAINING.ipynb
├── src
│   ├── app.py
│   ├── data_ingestion.py
│   ├── data_transformation.py
│   ├── model_trainer.py
│   ├── predict_pipeline.py
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
├── artifacts
│   ├── model.pkl
│   └── preprocessor.pkl
├── requirements.txt
├── setup.py
├── .gitignore
└── README.md
```




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
```
## Notebooks

1. **EDA STUDENT PERFORMANCE.ipynb**: This notebook contains exploratory data analysis (EDA) and insights on the dataset.
2. **MODEL TRAINING.ipynb**: This notebook is dedicated to model training, feature engineering, and model evaluation.

## Scripts Overview

- **app.py**: Main application script that ties together all components to run the churn prediction.
- **data_ingestion.py**: Handles the ingestion of raw data into the pipeline.
- **data_transformation.py**: Transforms and cleans the raw data, preparing it for model training.
- **model_trainer.py**: Contains the logic for training different machine learning models.
- **predict_pipeline.py**: Defines the pipeline for making predictions using the trained model.
- **utils.py**: Provides utility functions that are used across different scripts.
- **exception.py**: Custom exception classes for robust error handling.
- **logger.py**: Sets up logging for monitoring and debugging purposes.

## Model and Preprocessor

- **model.pkl**: The serialized machine learning model trained to predict churn.
- **preprocessor.pkl**: The serialized preprocessor for data transformation and feature engineering.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.









