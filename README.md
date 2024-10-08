# Breast_Cancer_Prediction_App
# Overview
The Breast Cancer Diagnosis app is a machine learning-powered tool designed to assist medical professionals in diagnosing breast cancer. Using a set of measurements, the app predicts whether a breast mass is benign or malignant. It provides a visual representation of the input data using a radar chart and displays the predicted diagnosis and probability of being benign or malignant. The app can be used by manually inputting the measurements or by connecting it to a cytology lab to obtain the data directly from a machine. The connection to the laboratory machine is not a part of the app itself.

The app was developed as a machine learning exercice from the public dataset Breast Cancer Wisconsin (Diagnostic) Data Set. Note that this dataset may not be reliable as this project was developed for educational purposes in the field of machine learning only and not for professional use.

A live version of the application can be found on Streamlit Community Cloud.

# Usage
To start the app, simply run the following command:

"streamlit run app/main.py"

This will launch the app in your default web browser. You can then upload an image of cells to analyze and adjust the various settings to customize the analysis. Once you are satisfied with the results, you can export the measurements to a CSV file for further analysis.
