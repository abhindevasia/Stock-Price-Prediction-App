# Stock Price Prediction App

## Overview
This repository contains an interactive application for predicting stock prices using an LSTM (Long Short-Term Memory) deep learning model. The application is built with Streamlit for ease of use and includes a trained model, sample data, and supporting scripts for seamless deployment.

## Features
- **Interactive Web App**: Built using Streamlit for intuitive stock price forecasting.
- **Deep Learning Model**: Uses an LSTM model trained on historical market data for accurate predictions.
- **Visualization**: Displays historical data trends and predicted stock prices.
- **Modular Design**: Easy to extend or modify for new use cases.

## Repository Contents
- **`app.py`**: Streamlit application script for running the web interface.
- **`lstm_stock_price_model.keras`**: Pre-trained LSTM model for stock price prediction.
- **`market_data.csv`**: Sample dataset containing historical market data for testing.
- **`part_1_model_building.ipynb`**: Jupyter notebook detailing the model building and training process.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Stock-Price-Prediction-App.git
   cd Stock-Price-Prediction-App
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Requirements
The project dependencies are listed in `requirements.txt`. Key packages include:
- TensorFlow
- Streamlit
- Pandas
- NumPy
- Matplotlib

## Usage
1. Launch the Streamlit app using the instructions above.
2. Upload a new market data file or use the included `market_data.csv`.
3. View the predictions and data visualizations directly in the web interface.

## Model Details
- **Architecture**: LSTM neural network designed for time series forecasting.
- **Training**: The model was trained on historical stock price data with preprocessed features for optimal performance.
- **File**: The pre-trained model is stored as `lstm_stock_price_model.keras` and is loaded during app initialization.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for:
- Bug fixes
- Feature enhancements
- Model improvements

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


