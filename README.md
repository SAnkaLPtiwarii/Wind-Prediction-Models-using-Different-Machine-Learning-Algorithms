# Wind-Prediction-Models-using-Different-Machine-Learning-Algorithms
Wind Prediction using Random Forest Regression, LSTM, GRU (Gated-Recurrent-Unit), Convolution-LSTM

Objectives
Import and preprocess datasets from Gujarat and Karnataka.
Model wind speed data at 10 meters (WS10M) and 50 meters (WS50M) for both regions.
Prepare the data for time series forecasting, including normalization and shaping into sequences suitable for LSTM-based networks.
Define and train the models.
Evaluate the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² metrics.
Predict wind energy for the next 1-2 months.
Data
The datasets include several meteorological variables by year, month, and day, such as pressure (PS), wind speed at 10 meters (WS10M) and 50 meters (WS50M), and their respective maximum, minimum, and range values, among other parameters.

Installation
To run the notebook and reproduce the results, you need to have the following libraries installed:

NumPy
pandas
sci-kit-learn
TensorFlow
matplotlib
joblib
You can install these dependencies using pip:

pip install numpy pandas sci-kit-learn TensorFlow matplotlib joblib
