# House Price Prediction

## Description
This project involves developing a machine learning model for predicting house prices using Python, scikit-learn, and TensorFlow. The model is deployed as a web application using Flask.

## Contents
- `app.py`: Flask web application for interacting with the model.
- `final_dataset.csv`: Dataset used for training and testing the model.
- `RidgeModel.pkl`: Pickled model file for deployment.
- `index.html`: HTML template for the web application interface.

## Usage
1. Clone the repository:
git clone <repository_url>

2. Install dependencies:
pip install -r requirements.txt

3. Run the Flask web application:
python app.py

4. Access the application in your web browser at `http://localhost:5000`.

## How to Predict
- Enter the number of bedrooms, bathrooms, size, and zip code in the input form.
- Click the "Predict" button to get the predicted house price.

## Additional Notes
- Ensure that the necessary dependencies are installed before running the application.
- The model utilizes Ridge regression for predicting house prices.
- Handle unknown categories in the input data by replacing them with default values.
- The application runs in debug mode for development purposes.

## Requirements
- Python 3.x
- Flask
- pandas
- scikit-learn
- TensorFlow

