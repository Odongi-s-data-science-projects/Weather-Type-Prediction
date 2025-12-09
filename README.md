 # **Weather-Type-Prediction**
 A machine learning project to accurately predict the weather type (Cloudy, Rainy, Snowy, or Sunny) based on weather data features.

 
## **Description**

This repository contains the complete workflow for building, training, and evaluating a classification model to categorize daily weather conditions. The primary model used is the Random Forest Classifier, which achieved a high prediction accuracy of $98\%$ on the test set. The trained model is saved using joblib for easy deployment and inference.


## **Features**

1. Data Preprocessing: Cleaning and preparing raw weather data for model training.
2. Random Forest Model: Utilizes a highly effective ensemble model for classification.
3. High Accuracy: Demonstrates robust performance with an accuracy of $0.98$.
4. Model Persistence: Saves the trained model (weather_prediction_type.joblib) for reuse.
5. Detailed Evaluation: Includes a comprehensive classification report to analyze model performance across all weather classes.


## **Getting Started**

Prerequisites
To run this project, you need Python version 3.7+. It is highly recommended to use a virtual environment.


## **Usage**

The core analysis and model training are contained in the Jupyter Notebook.

Train the Model

To retrain the model and reproduce the results:

  1. Open the Jupyter Notebook: Weather Type prediction.ipynb.
  2. Run all cells sequentially.
  3. The trained model will be saved as weather_prediction_type.joblib.
