# Yahoo Stocks Predictor

This project focuses on predicting the highest values of stock prices for Yahoo stocks using Long Short-Term Memory (LSTM) models. The dataset used for this project contains historical stock price data for Yahoo stocks.

## Requirements

- Python 3.x
- pandas
- PyTorch
- TensorFlow
- scikit-learn

## Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/yahoo-stocks-predictor.git
```

2. Install the required dependencies:

```
pip install pandas torch tensorflow scikit-learn
```

## Usage

1. Navigate to the project directory:

```
cd yahoo-stocks-predictor
```

2. Run the script to develop and train the LSTM model for predicting the highest values of stock prices:

```
python train_lstm_model.py
```

This script will train the LSTM model using historical stock price data, incorporating Dropout and Batch Normalization layers for optimization.

3. After training the model, you can use it to predict the highest stock values for the next 100 days and plot the results:

```
python predict_and_plot.py
```

This script will generate predictions for the highest stock values for the next 100 days based on the trained LSTM model and plot the results.

## Model Architecture

The LSTM model is a type of recurrent neural network (RNN) architecture designed to process and predict sequences of data. It consists of LSTM layers followed by fully connected layers. Dropout layers are added to prevent overfitting by randomly dropping neurons during training. Batch Normalization layers ensure stable training by normalizing the activations.

## Results

After training the LSTM model and generating predictions for the next 100 days, the highest stock values are plotted to visualize the predicted trends.

## Contributors

- Aruzhan Oshakbayeva

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
