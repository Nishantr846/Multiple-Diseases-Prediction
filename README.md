
# Multiple Disease Prediction System

A Machine Learning-based system that predicts multiple diseases, including **Diabetes**, **Heart Disease**, **Parkinson's Disease**, and **Breast Cancer**, based on user input. This project uses various machine learning models and provides predictions in real-time using a **Streamlit** web interface.

## Features

- **Diabetes Prediction**: Predicts whether a person is diabetic or not based on various health parameters.
- **Heart Disease Prediction**: Predicts the likelihood of heart disease based on user-provided data.
- **Parkinson's Disease Prediction**: Uses voice-related features to detect Parkinson's disease.
- **Breast Cancer Prediction**: Classifies breast cancer as either malignant or benign based on several diagnostic metrics.

## Installation

### Prerequisites

Make sure you have the following installed on your local machine:

- **Python** (version 3.6 or higher)
- **Streamlit** for running the web interface
- **Pickle** for loading the pre-trained machine learning models

You can install the necessary libraries using `pip`:


  - pip install pickle-mixin
  - pip install scikit-learn
  - pip install numpy
  - pip install pandas
  - pip install streamlit
  


## How to Run

1. Clone this repository to your local machine:


git clone https://github.com/Nishantr846/Multiple-Diseases-Prediction.git
cd Multiple-Diseases-Prediction


2. Run the Streamlit app:

streamlit run multiple disease pred.py


This will start a local server and open the application in your browser.

## How It Works

- The user selects a disease prediction option from the sidebar.
- For each prediction model, users are prompted to input various medical parameters.
- Once the inputs are provided, the user clicks on the "Test Result" button.
- The system processes the inputs through the corresponding machine learning model and provides the diagnosis.

## Models

This system uses pre-trained machine learning models:

- **Diabetes Model**: A model trained to predict the likelihood of diabetes.
- **Heart Disease Model**: A model that predicts the presence of heart disease.
- **Parkinson's Disease Model**: A model that classifies the risk of Parkinson's disease based on voice features.
- **Breast Cancer Model**: A model that predicts whether breast cancer is malignant or benign.

These models have been saved in **Pickle** format and are loaded dynamically when the app is run.


### Contact : 
- Nishant Kumar
- nishantr846@gmail.com
- https://www.linkedin.com/in/nishantr846/
