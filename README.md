
#  Predict Prices of Airline Tickets using Machine Learning

This project uses machine learning techniques to predict the price of airline tickets based on various factors such as airline name, departure and arrival times, duration, number of stops, source, and destination.

## 📌 Table of Contents

* [Overview](#overview)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Model Used](#model-used)
* [How to Run](#how-to-run)
* [Results](#results)
* [Future Work](#future-work)
* [Contributing](#contributing)

---

## 📖 Overview

Airline ticket prices can vary significantly depending on the time, airline, stops, and route. This project aims to build a regression model that can accurately predict ticket prices based on these parameters. It can help travelers plan better and airline companies adjust pricing strategies.

---

## 📂 Dataset

The dataset used is a cleaned version of publicly available airline ticket data. It includes the following columns:

* **Airline**: The name of the airline.
* **Date\_of\_Journey**: The date of the journey.
* **Source**: The starting city.
* **Destination**: The arrival city.
* **Route**: Route of the journey.
* **Dep\_Time**: Departure time.
* **Arrival\_Time**: Arrival time.
* **Duration**: Total travel time.
* **Total\_Stops**: Number of stops.
* **Additional\_Info**: Extra information about the flight.
* **Price**: Ticket price (target variable).

---

## 🛠️ Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib / Seaborn (for visualization)
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## ✅ Features

* Data Cleaning and Preprocessing
* Feature Engineering
* Encoding Categorical Data
* Model Training and Evaluation
* Price Prediction for new data

---

## 🤖 Model Used

We experimented with various regression models. The final model selected is:

* **Random Forest Regressor**
  Selected for its accuracy, performance, and ability to handle non-linear data well.

Other models tried:

* Linear Regression
* Decision Tree Regressor
* XGBoost Regressor

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/airline-price-prediction.git
   cd airline-price-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Airline_Ticket_Price_Prediction.ipynb
   ```

4. Predict prices by providing input in the test cell or using the prediction function.

---

## 📊 Results

* Best RMSE: 45.48144
* Best R² Score: 0.7629
* Feature importance was found in:

  * Airline type
  * Total travel duration
  * Number of stops
  * Departure and arrival time slots

---

## 🔮 Future Work

* Deploy model using Flask or Streamlit as a web application.
* Add real-time price scraping and prediction.
* Improve accuracy with more advanced models like LSTM for time-series data.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

---

Let me know if you'd like a `requirements.txt` or a sample Streamlit UI for this project!
