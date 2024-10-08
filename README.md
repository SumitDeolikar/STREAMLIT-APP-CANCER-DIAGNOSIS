# BREAST-CANCER-DIAGNOSIS-PREDICTOR-APP

# Overview

The Breast Cancer Diagnosis app is a machine learning-powered tool designed to assist medical professionals in diagnosing breast cancer. Using a set of measurements, the app predicts whether a breast mass is benign or malignant. It provides a visual representation of the input data using a radar chart and displays the predicted diagnosis and probability of being benign or malignant. The app can be used by manually inputting the measurements or by connecting it to a cytology lab to obtain the data directly from a machine. The connection to the laboratory machine is not a part of the app itself.

The app was developed as a machine learning exercice from the public dataset Breast Cancer Wisconsin (Diagnostic) Data Set. Note that this dataset may not be reliable as this project was developed for educational purposes in the field of machine learning only and not for professional use.

# How to run this app?

You can run this inside a virtual environment to make it easier to manage dependencies.
Please follow the below steps to run the app - 

# 1. The first step is to create virtual environment . Run the below command on your cmd -
    python -m venv test

   test is the name of virtual environment created

# 2. Second step is to activate the environment -
    test\Scripts\activate

# 3. To install the required packages, run -
    pip install -r requirements.txt

# 4 . Usage

To start the app, simply run the following command - 
   streamlit run app/main.py


    

