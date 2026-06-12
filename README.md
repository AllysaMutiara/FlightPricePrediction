# Flight Price Prediction

A machine learning project to predict flight ticket prices based on flight information such as airline, travel class, flight duration, departure and arrival times, source and destination cities, number of stops, and days left before departure.

## Project Structure

* `flightPricePrediction.ipynb` — Jupyter Notebook containing data preprocessing, model training, evaluation, and analysis.
* `flight_price.csv` — Dataset used for training and testing the model.

## Dataset

The dataset includes features such as:

* Airline
* Source City
* Departure Time
* Stops
* Arrival Time
* Destination City
* Travel Class
* Duration
* Days Left Before Departure
* Price (target variable)

The notebook covers:

1. Data loading and exploration
2. Data preprocessing and encoding
3. Feature analysis
4. Model training
5. Model evaluation
6. Feature importance analysis

## Model Overview

Model used:

* Random Forest Regressor

Evaluation metrics:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

## Model Performance
* R² Score: 0.9848 
* MAE: 1086.73 
* RMSE: 2801.27 

## Key Findings

* Travel class was identified as the most influential feature, contributing approximately 87.99% of the model's predictive power.
* Flight duration and days left before departure were also important factors affecting ticket prices.
* The model achieved strong performance with minimal signs of overfitting, as indicated by the small gap between training and testing scores.

## License

This project is licensed under the MIT License.
