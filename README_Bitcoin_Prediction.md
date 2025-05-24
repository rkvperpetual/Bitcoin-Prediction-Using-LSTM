
# 📈 Bitcoin Price Prediction Using LSTM

This project implements a Long Short-Term Memory (LSTM) neural network to predict Bitcoin prices based on historical data. Leveraging deep learning techniques, the model aims to capture temporal dependencies in Bitcoin price movements to forecast future trends.

## 🚀 Features

- **Data Preprocessing**: Cleans and prepares historical Bitcoin price data for modeling.
- **LSTM Model**: Constructs and trains an LSTM neural network for time series prediction.
- **Model Evaluation**: Assesses model performance using appropriate metrics and visualizations.
- **Prediction Visualization**: Plots actual vs. predicted prices to visualize model accuracy.

## 🗂️ Project Structure

```
Bitcoin-Prediction-Using-LSTM/
├── experiments.ipynb           # Jupyter Notebook with data preprocessing, model training, and evaluation
├── bitcoin_price.csv           # Dataset containing historical Bitcoin prices
├── lstm_model.h5               # Saved LSTM model
├── requirements.txt            # List of Python dependencies
└── README.md                   # Project documentation
```

## 📊 Dataset

- **Source**: The dataset `bitcoin_price.csv` contains historical Bitcoin price data.
- **Features**: Includes attributes such as Date, Open, High, Low, Close, Volume, etc.
- **Usage**: The 'Close' price is primarily used for training the prediction model.

## 🧠 Model Training

- **Architecture**: The LSTM model is designed to capture temporal patterns in the price data.
- **Training**: The model is trained on the preprocessed data to learn the underlying trends.
- **Evaluation**: Model performance is evaluated using metrics like Mean Squared Error (MSE).

## 🧪 Installation and Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/rkvperpetual/Bitcoin-Prediction-Using-LSTM.git
   cd Bitcoin-Prediction-Using-LSTM
   ```

2. **Create a Virtual Environment (Optional but Recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**

   ```bash
   jupyter notebook experiments.ipynb
   ```

   Follow the notebook cells to preprocess data, train the model, and visualize predictions.

## 📌 Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow
- keras

Ensure all dependencies are installed by running:

```bash
pip install -r requirements.txt
```

## 📈 Results

The model's predictions are visualized alongside actual Bitcoin prices to assess accuracy. These plots help in understanding how well the model captures the price trends.

## 🤝 Contributing

Contributions are welcome! If you'd like to enhance this project:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request detailing your changes.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
