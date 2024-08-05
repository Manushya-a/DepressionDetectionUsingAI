# Early Detection of Depression Using Machine Learning on EEG Data

## Overview

Depression remains a significant global health concern, demanding effective diagnostic tools for timely intervention. This project investigates the utilization of machine learning models for the early detection of depression through the analysis of Electroencephalography (EEG) data. The study aims to develop robust and accurate diagnostic models to discern neurophysiological patterns associated with depressive states.

## Key Features

- **Machine Learning Models**: Implementation of various algorithms including:
  - DecisionTreeClassifier
  - KNeighborsClassifier
  - Support Vector Classifier
  - Support Vector Machine
  - Gaussian classifier
  - Random forest classifier
  - AdaBoost classifier
  - Multi-Layer Perceptron
- **EEG Data Analysis**: Comprehensive preprocessing steps including artifact removal, segmentation, and feature extraction.
- **Cross-Validation**: Ensuring model performance and generalizability.

## Project Structure

- `data/`: Contains the EEG data used for training and testing.
- `notebooks/`: Jupyter notebooks demonstrating the preprocessing, feature extraction, and model implementation.
- `models/`: Saved machine learning models.
- `results/`: Performance metrics and evaluation results.
- `src/`: Source code for preprocessing, model training, and evaluation.

## Installation

To install the necessary dependencies for this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo
    ```
3. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To preprocess the EEG data and train the machine learning models, follow these steps:

1. Preprocess the EEG data:
    ```bash
    python src/preprocess_data.py
    ```
2. Train the machine learning models:
    ```bash
    python src/train_models.py
    ```
3. Evaluate the models:
    ```bash
    python src/evaluate_models.py
    ```

## Results

The findings of the study demonstrate the efficacy of the selected machine learning models in accurately identifying depressive states based on distinct EEG patterns. The application of cross-validation ensures the reliability of the models in practical scenarios.


## Acknowledgements

This research contributes significantly to the evolving domain of mental health diagnostics, underscoring the potential of machine learning in the early and accurate detection of depression.
