Bitcoin Price Prediction using Hybrid Sentiment Analysis and Deep Learning

📌 Project Overview

This research project aims to forecast Bitcoin prices by combining Hybrid Sentiment Analysis (using Twitter sentiment data) and Deep Learning approaches on historical Bitcoin market data.
The model leverages both market indicators and public sentiment to improve prediction accuracy.
It is implemented using Python, Pandas, NumPy, Scikit-learn, TensorFlow/Keras, and Natural Language Processing (NLP) techniques.



📂 Dataset

The datasets used in this project are available on Kaggle:

📈 Bitcoin Historical Market Data (https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)

🐦 Bitcoin Tweets Dataset (https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets)


> Note: Due to their large size, the datasets are not included in this repository. Please download them from the links above and place them in a data/ folder before running the code.



⚙️ Features of the Project

Hybrid sentiment analysis combining positive, negative, and neutral sentiments from tweets.

Data preprocessing for both time-series financial data and textual sentiment data.

Deep learning model for price forecasting.

Evaluation metrics including RMSE, MAE, and MAPE.

Visualization of predicted vs. actual Bitcoin prices.





📦 Installation & Requirements

Make sure you have Python 3.8+ installed. Install required dependencies:

pip install -r requirements.txt




▶️ How to Run

1. Clone the repository



git clone https://github.com/<your-username>/bitcoin-price-prediction.git
cd bitcoin-price-prediction


2. Download datasets from the provided Kaggle links.


3. Place datasets inside the data/ folder.


4. Run the Jupyter Notebook or Python script:



    jupyter notebook bitcoin_price_prediction.ipynb




📊 Results

The model achieves high accuracy by integrating sentiment analysis with historical price data.
Sample result plots and metrics are provided in the results/ folder.





📜 License

This project is licensed under the no License.




🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
