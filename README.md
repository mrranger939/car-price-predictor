

# Car Price Predictor

This is a Car Price Predictor application built using Machine Learning (Linear Regression) and a web interface created with Flask.

## Overview

This project aims to predict the price of a car based on various input features such as company, model, year of purchase, fuel type, and the number of kilometers traveled. The machine learning model is trained using linear regression.

## Features

- **Select Company**: Choose the car company.
- **Select Car Model**: Select the specific car model.
- **Select Year of Purchase**: Enter the year the car was purchased.
- **Select Fuel Type**: Choose between petrol or diesel.
- **Enter Number of km travelled**: Input the number of kilometers the car has traveled.
- **Predict Price**: Click the button to get the predicted price of the car.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/car-price-predictor.git
   ```
2. Change to the project directory:
   ```sh
   cd car-price-predictor
   ```
3. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:
   ```sh
   python app.py
   ```
2. Open your web browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```
3. Use the web interface to input the car details and get the predicted price.

## Files

- `app.py`: The main Flask application file.
- `LinearRegressionModel.pkl`: The pre-trained machine learning model.
- `templates/`: Folder containing the HTML template(s).
- `static/`: Folder containing static files like CSS.
- `requirements.txt`: List of required Python packages.

## Example

Here is an example of the application in use:


![image](https://github.com/mrranger939/car-price-predictor/assets/137317392/662b4381-c1a4-450b-a7ab-9a2885189f92)


## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

