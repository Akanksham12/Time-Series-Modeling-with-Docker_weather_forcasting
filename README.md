# Time-Series-Modeling-with-Docker_weather_forcasting

##Weather Forecasting with LSTM
This project focuses on weather forecasting using an LSTM-based model. It uses historical weather data, including various parameters like pressure, temperature, wind speed, etc., to predict future temperatures.

 ```bash
     git clone https://github.com/Akanksham12/weather-forecast-lstm.git
     cd weather-forecast-lstm
     Install Dependencies: Ensure you have the necessary dependencies installed. You can use pip:

 ```bash
     pip install pandas matplotlib tensorflow
     Dataset and Pre-trained Model:

***Project Structure:***
weather_data.csv: Dataset containing weather parameters.
weather_forecasting_lstm.ipynb: Jupyter Notebook containing the code for the project.
Usage
load and preprocess the data, create the LSTM model, and train it.
Evaluate the model's performance on the test data, visualizing loss and accuracy.
The notebook provides insights into feature correlation through a heatmap.
Visualizations of raw data and prediction examples are included for better understanding.
Features
The selected parameters for weather forecasting include:

Pressure
Temperature
Temperature in Kelvin
Temperature (dew point)
Relative Humidity
Saturation vapor pressure
Vapor pressure
Vapor pressure deficit
Specific humidity
Water vapor concentration
Airtight
Wind speed
Maximum wind speed
Wind direction in degrees

***Visualization***
Explore the raw data visualizations and feature correlation heatmap provided in the notebook. These visualizations help understand the dataset and the relationships between different weather parameters.

***Training the Model***
The LSTM model is trained with specific hyperparameters, such as past and future time steps, learning rate, batch size, and epochs. Adjust these parameters based on your requirements.

