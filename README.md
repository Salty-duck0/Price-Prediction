# Stock Price Prediction Repository

Welcome to the Stock Price Prediction repository! This repository contains code for predicting stock prices using two different techniques: Long Short-Term Memory (LSTM) neural networks and Linear Regression.

## File Structure
- data/
  - TATA STEEL.csv
- resources/
  - feature selection.pdf
  - Stock-Market-Prediction-Using-LSTM-Recurrent-Neural-Network.pdf
- LSTM.ipynb
- Linear_reg.ipynb



## LSTM.ipynb

### Code Overview
The `LSTM.ipynb` Jupyter Notebook includes code for predicting stock prices using LSTM neural networks. It performs the following steps:

1. Data loading and preprocessing.
2. Scaling the data using Min-Max scaling.
3. Creating training and testing datasets.
4. Building an LSTM model.
5. Training the model.
6. Making predictions on the test data.
7. Visualizing the predictions.

### Getting Started
1. Install the required libraries.
2. Ensure you have access to the dataset at the specified URL.
3. Run the code cells in this notebook to perform stock price prediction.

### Prerequisites
- Python
- pandas
- numpy
- scikit-learn
- keras
- tensorflow
- matplotlib


### Acknowledgments
- Inspiration from [Stock-Market-Prediction-Using-LSTM-Recurrent-Neural-Network.pdf](resources/Stock-Market-Prediction-Using-LSTM-Recurrent-Neural-Network.pdf).
- Feature selection techniques outlined in [feature selection.pdf](resources/feature-selection.pdf).

## Linear_reg.ipynb

### Code Overview
The `Linear_reg.ipynb` Jupyter Notebook includes code for predicting stock prices using Linear Regression. It performs the following steps:

1. Data loading and preprocessing.
2. Feature scaling using Min-Max scaling.
3. Shuffling and splitting the dataset into training and testing sets.
4. Building a Linear Regression model.
5. Training the model.
6. Making predictions on the test data.
7. Calculating and displaying prediction error.

### Getting Started
1. Install the required libraries.
2. Ensure you have access to the dataset at the specified URL.
3. Run the code cells in this notebook to perform stock price prediction.

### Prerequisites
- Python
- pandas
- numpy
- scikit-learn
- matplotlib



### Acknowledgments
- Feature selection techniques outlined in [feature selection.pdf](resources/feature-selection.pdf).
- Dataset used for prediction: [TATA-STEEL.csv](data/TATA-STEEL.csv).

## Contact
Feel free to contact me with any questions or suggestions related to this repository.

Happy coding!
