Air Passengers Forecasting using LSTM
This project applies a Long Short-Term Memory (LSTM) neural network to forecast the number of monthly airline passengers using the AirPassengers dataset, which contains data from 1949 to 1960.

Files Included
AirPassengers.csv: Dataset with monthly totals of international airline passengers.

lstm_air_passengers.py: Script for data preprocessing, model training, prediction, and plotting.

README.md: Project overview and usage instructions.

Dataset Description
The dataset records monthly airline passenger counts from January 1949 to December 1960. It contains two columns:

Month: Time period (month and year)

Passengers: Number of passengers during that month

Project Workflow
Load and preprocess the dataset.

Normalize the passenger data.

Create input-output sequences for time series modeling.

Split the data into training and testing sets.

Build and train an LSTM neural network.

Predict passenger numbers and compare with actual values.

Visualize the results with a plot.

Model Overview
The LSTM model includes:

One LSTM layer with 50 units and ReLU activation.

A Dense output layer with a single neuron.

The Adam optimizer and mean squared error as the loss function.

Trained for 100 epochs with a batch size of 16.

Sequence length used for prediction: 12 months.

Output
The model outputs a line plot comparing actual and predicted passenger values, allowing visual inspection of model performance.

Requirements
The project uses Python libraries including TensorFlow, pandas, NumPy, scikit-learn, and matplotlib.
