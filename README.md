# CodeAlpha-ML-Disease_Prediction_from-Medical_Data_03

This project builds a model to predict the likelihood of various diseases based on medical data such as symptoms and patient history. The model uses classification algorithms to analyze labeled medical records and accurately predict diseases.

Dataset
The dataset contains medical records with details about symptoms, patient history, and corresponding disease labels. Before running the model, ensure the dataset is preprocessed and ready for training.

How to Add the Dataset (CSV)
Download the dataset as a .csv file.
Place the .csv file in the project folder.
In the code, load the CSV file like this:

Code:-
import pandas as pd

# Replace 'your_dataset.csv' with the actual name of your CSV file

data = pd.read_csv('your_dataset.csv')
How to Run the Project
Install Python: Make sure Python is installed on your system.
Install Required Libraries: Run the following command to install necessary libraries:

bash Code :-
pip install pandas scikit-learn matplotlib
Run the Code: Open the code file and run the script in your Python environment.
Add the CSV File: Ensure the dataset file is in the same directory and correctly loaded into the code.

Model Performance

The model achieved an accuracy of 97.62%. The precision, recall, and F1-score for each disease class are also reported to give deeper insights into its performance for different diseases.

This README gives clear instructions on how to run the project, add the CSV file, and understand the model's performance.
