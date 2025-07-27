Cryptocurrency Price Prediction Web App 

An interactive web application for analyzing historical data and forecasting future price movements of various cryptocurrencies using multiple machine learning models.

🌟 Project Overview

This project is a Flask web application that performs price prediction based on a user-selected cryptocurrency and a machine learning model. The application fetches raw data from the Binance API, cleans it, and stores it in CSV format. Subsequently, it generates predictions using the selected model and presents the results to the user with interactive charts.

✨ Key Features

Dynamic Crypto Selection: Users can choose from many popular cryptocurrencies like BTC, ETH, DOGE, etc., via the interface.

Multi-Model Support: Offers different machine learning models for prediction, including Linear Regression, XGBoost, and LSTM.

Interactive Web Interface: A user-friendly interface developed with Flask.

Comprehensive Data Visualization:

A main chart comparing historical data with the model's predictions.

A 30-day future price forecast chart.

Automated Data Pipeline: Handles fetching data from the Binance API, cleaning it, and converting it to CSV format.

🛠️ Technologies Used

The following technologies and libraries were used in this project:

Backend:

Python: The main programming language.

Flask: For the web server and interface management.

Data Processing & Analysis:

Pandas: For data manipulation, cleaning, and CSV operations.

NumPy: For numerical computations.

python-binance: For fetching data from the Binance API.

Machine Learning:

Scikit-learn: For baseline models like Linear Regression and data preprocessing tools.

XGBoost: For a high-performance Gradient Boosting model.

TensorFlow (Keras): For the deep learning-based LSTM model.

Data Visualization:

Matplotlib & Seaborn: For creating and saving the prediction charts.

Frontend:

HTML & CSS: For the basic interface structure and styling.

📸 Application Interface

Home Page & Selection Screen	Prediction Results & Charts

<img width="800" height="800" alt="Ekran görüntüsü 2025-07-27 153747" src="https://github.com/user-attachments/assets/b4578b26-cf7a-47e9-af50-9aa37951983a" />

<img width="800" height="800" alt="Ekran görüntüsü 2025-07-27 153704" src="https://github.com/user-attachments/assets/8923c268-82fe-4185-b64d-312deb89aa83" />
