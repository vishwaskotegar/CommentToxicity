# Toxicity Detection Notebook

This Jupyter Notebook demonstrates a machine learning pipeline for detecting toxic comments. It includes data preprocessing, model training, evaluation, and deployment using an interactive web interface.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Overview](#notebook-overview)
- [Results](#results)


## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/vishwaskotegar/CommentToxicity.git
    cd CommentToxicity
    ```

2. **Install required packages**:
    Make sure you have Python 3.10 installed. 

## Usage

1. **Run the notebook**:
    Open `Toxicity.ipynb` in Jupyter Notebook or JupyterLab and run the cells sequentially.

2. **Interactive interface**:
    Towards the end of the notebook, a Gradio interface is provided to test the toxicity detection model interactively. Follow the instructions in the notebook to launch the interface.

## Notebook Overview

1. **Introduction**:
    - Overview of the problem and objectives.

2. **Data Loading and Preprocessing**:
    - Load and preprocess the dataset for training the model. This includes vectorizing the data.

3. **Model Training**:
    - Train a machine learning model to classify comments as toxic or non-toxic. Common Layers used include Bidirectional, LSTM, Embedding and Fully connected Dense layers.

4. **Model Evaluation**:
    - Evaluate the trained model using appropriate metrics like accuracy, precision, and Frecall.

5. **Display Results**:
    - Display the model using Gradio to create an interactive web interface for real-time toxicity detection.

## Results

The notebook provides detailed results of the model's performance, including evaluation metrics and examples of predictions on test data. The interactive Gradio interface allows users to input comments and see the model's toxicity prediction.

