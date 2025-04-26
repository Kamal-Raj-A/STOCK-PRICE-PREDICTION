# 🚀 STOCK PRICE PREDICTION
Predict future stock prices based on historical data using a machine learning model built with Keras, and deploy it as a simple, user-friendly web application using Flask.

---
## 🎯 Objective

1. Data Collection and Preprocessing:

* Gather historical stock market data (such as open, high, low, close, and volume).

* Clean, normalize, and prepare the data for model training.

2. Model Development:

* Build and train a deep learning model (using Keras, e.g., LSTM) to predict future stock prices.

* Tune model parameters to improve prediction accuracy and prevent overfitting.

3. Model Evaluation:

* Evaluate the model’s performance on unseen test data.

* Use appropriate metrics like Mean Squared Error (MSE) or Root Mean Squared Error (RMSE).

4. Model Deployment:

* Save the trained model in an appropriate format (such as .h5).

* Develop a Flask web application to deploy the model for real-time predictions.

5. User Interface Design:

* Create a simple, user-friendly web interface for users to input stock details and view predictions.

* Visualize actual vs predicted prices using graphs or charts.

6. Real-World Usability:

* Provide an accessible tool for investors, traders, and learners to forecast future stock prices based on historical data.
Make complex AI predictions accessible through a friendly web portal.

---

## 🛠️ Tech Stack

### Core Technologies Used:
1. Frontend:
  * HTML (structure of the web pages)
  * CSS (styling like colors, fonts, spacing)
  * Bootstrap (for quick, responsive design and nice-looking buttons, forms, and layouts)
2. Backend:
  * Flask - A lightweight Python web framework to handle routing, server-side logic, and API endpoints. It connected the frontend with the machine learning model.
  * Keras (TensorFlow backend) - Used to build, train, and load the deep learning model (like LSTM) for stock price predictions. The model was saved (e.g., as a .h5 file) and loaded during runtime for making predictions.
  * Python - All backend logic (data preprocessing, model loading, prediction generation) was written in Python
3. Database:
  * yfinance is a Python library that allows users to access real-time and historical stock market data from Yahoo Finance.
  * It simplifies fetching data such as stock prices, volumes, and financial indicators using simple Python code.
  * In this project, yfinance was used to: Retrieve live stock market data based on user input (e.g., stock ticker). Provide historical data for model prediction and visualization.
---
## ✨ Key Features
1. Real-Time Stock Data Fetching
  * Utilizes the yfinance library to fetch live and historical stock data from Yahoo Finance for any given stock ticker.
2. Deep Learning Model
  * Built with Keras (TensorFlow backend), the project uses a deep learning model (likely LSTM) to predict future stock prices based on historical data.
3. Prediction Interface
  * Allows users to input a stock ticker and get a future price prediction, which is displayed on the web interface.
4. Flask Web Application
  * Developed a user-friendly Flask web app where users can interact with the model, input stock tickers, and view predictions.
5. Data Visualization
  * The application presents predictions using Matplotlib or Plotly to visually compare actual vs predicted stock prices.
6. Simple and Intuitive User Interface
  * The frontend is built using HTML, CSS, and Bootstrap, ensuring that the app is responsive and easy to use.
7. Model Saving and Loading
  * The trained deep learning model is saved in a .h5 file format and can be reloaded for real-time predictions, reducing model retraining time.
8. Backend Logic for Predictions
  * The backend uses Python and Flask to handle all logic, including fetching data, processing user input, and running the model to generate predictions.
9. Scalability
  * The project is designed in a modular way, allowing for easy integration of additional stock analysis features or more complex models.
    
---

## 🧪 How to Run the Project
Project folder link : https://drive.google.com/drive/folders/1GmNZ-Oj144IOdY8AbjFWndL_aXrs-890?usp=drive_link
### Requirements:
- pip install scikit-learn
- pip install plotly
- pip install tensorflow
- pip install matplotlib
- pip install yfinance
- pip install flask
### Start to run:
1. Open the project folder in VS code.
2. Select the option "Run python file in dedicated terminal"
   
   ![image](https://github.com/user-attachments/assets/c7a33c85-29e9-4b61-82bf-c96db759c455)
   
  Note : After opening the folder make sure that no errors in the libraries.
  If shows download it using "pip install requirements.txt" command.
  
3. It shows like this:
 
 ![image](https://github.com/user-attachments/assets/25f16891-b9bb-48de-aed9-7cac9b5060b3)
 
4. Then use the command "python -m streamlit run app.py"
  It will redirect you to the app website.

![image](https://github.com/user-attachments/assets/45b03625-ac4c-4d90-aa83-77acdc27d033)

5. Now you can enter the ticker symbols for the specific stock company (example: AAPL, TSLA, MSFT...etc.,).
6. You can see the Original vs Predicted stock prices in the Graph.

   ![image](https://github.com/user-attachments/assets/66c15c20-10ba-4418-82d8-bdf7f13c22ee)

---

## 🧬 Future Scope:

This project can be enhanced by integrating more advanced deep learning models like GRU or Transformer architectures to improve prediction accuracy. Real-time data streaming and sentiment analysis from news or social media can also be incorporated for smarter forecasting. Additionally, deploying the application on cloud platforms and developing interactive dashboards would make it more accessible and user-friendly. Expanding the system into portfolio management and mobile app integration are also promising future enhancements.

---
