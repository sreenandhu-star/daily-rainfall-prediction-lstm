# daily-rainfall-prediction-lstm
Daily rainfall prediction using LSTM and the IMD Rainfall Dataset 2022.

 Daily Rainfall Prediction Using LSTM
Project Overview

This project predicts next-day rainfall for a selected district using the IMD Rainfall Dataset 2022 from Kaggle.

Dataset
Source: IMD Rainfall Dataset 2022
Data: Daily rainfall measurements for Indian districts.
Algorithm

Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN), is used for time-series regression.

Methodology
Load and preprocess the rainfall dataset.
Select one district.
Handle missing values.
Normalize rainfall measurements using Min-Max scaling.
Create input sequences using the previous seven days.
Split the data chronologically into 80% training and 20% testing.
Train the LSTM model.
Evaluate using MAE and RMSE.
Plot actual versus predicted rainfall.
Generate seven-day recursive predictions.
Technologies Used
Python
Pandas and NumPy
Matplotlib
Scikit-learn
TensorFlow / Keras
Google Colab
Evaluation

The model is evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

Insert the actual metric values obtained from the completed notebook run.

Limitations

The model uses historical rainfall alone and one year of data. Its predictions are experimental and are not a replacement for official weather forecasts.
