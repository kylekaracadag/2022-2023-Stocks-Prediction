# 2022-2023-Stocks-Prediction

2022-2023 Stocks Prediction is an ongoing project developed by the Artificial Intelligence club of the University of Central Florida.

  - [Getting Started](#Getting-Started)
  - [Navigating the Repository](#Navigating-the-Repository)
  - [Results](#Results)

## Getting Started

Please follow the instructions below to install the components required for this project:

### Clone the Repository
Opening your terminal and naviagte to your preffered file path.
Type the followng command:
```
git clone https://github.com/kylekaracadag/Stocks-Prediction.git
```

### Install Libraries
Using the same file path install the libraries by typing the following command:
```
pip install -r requirements.txt
```

## Navigating the Repository
### Folders:
- Datasets: Includes all the datasets that were used to train the model. <br>
- Introduction_to_ML: A basic introduction to machine learning with Python for members in our team new to artificial intelligence. <br>
- Models: Downloaded models that can be reused without having to re-train the model for making stocks predictions. <br>
- Predictions: csv files with datapoints that include all the stock price predictions that were made. <br>
- Webapp: This folder contains the neccessary files to run our web application which displays all the charts from Data_Visualization.ipynb.<br>

### Files:
- LSTM_Model.ipynb: The main notebook for our project. The model that was used to make predictions that can be found in Data_Visualization.ipynb or [Results](#Results).<br>
- Data_Visualization.ipynb: This file is used to visualize both the actual data and predicted data in line chart and candle stick forms. The candle stick charts do not get displayed if the file is opened from GitHub but the screenshots are posted in "Results". Developers can also choose to manually run the file for a more detailed chart.<br>
- ARIMA_Model.ipynb: The ARIMA model we implemented using Python to make predictions on the Open/Close price.<br>
- dataset.ipynb: Program that is used to extract datasets from yfinance given a specific time frame. The dataset is updated every week and posted to Datasets/MSFT_2023-01-13.csv . The dataset consists of Open/Close/High/Low prices for every minute as well as the corresponding date time from 2023-01-13 to today. <br>
- requirements.txt: Text file that contains all the required libraries for this project.<br>

## Results
### Real MSFT Candle Sticks
![image](https://user-images.githubusercontent.com/72484649/225200422-0c3d43b3-327d-4b11-99f6-c48338362387.png)

### Predicted MSFT Candle Sticks
![image](https://user-images.githubusercontent.com/72484649/225200466-564c7372-4957-4752-a56f-5910cde0f515.png)


