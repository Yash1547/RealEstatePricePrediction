# Real Estate Price Prediction

## Overview
This project aims to build a machine learning model for predicting real estate prices based on various features such as location, square footage, number of bedrooms, and number of bathrooms. The model is trained on a dataset obtained from a real estate agency, and it is deployed as a web application using Flask framework. Users can input property details, and the model will provide an estimated price based on the input.

## Features
- **Data Cleaning:** The dataset is cleaned to handle missing values, outliers, and inconsistencies.
- **Feature Engineering:** Additional features are derived from existing ones to improve model performance.
- **Outlier Removal:** Outliers in the dataset are identified and removed to improve model accuracy.
- **Machine Learning Model:** A regression model (e.g., Linear Regression, Lasso Regression, or Decision Tree Regression) is trained to predict real estate prices.
- **Flask Backend:** The model is deployed as a backend server using Flask, allowing users to interact with it via HTTP requests.
- **Web Interface:** A simple web interface is created using HTML, CSS, and JavaScript to provide a user-friendly experience for entering property details and viewing predicted prices.
## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/real-estate-price-prediction.git
2. Install dependencies:
   ```terminal
   pip install -r requirements.txt
3. Run the Flask application:
   ```terminal
   python app.py

##Dataset
The dataset used in this project contains real estate listings with various features such as location, size, and price. It was obtained from Kaggle and preprocessed for use in the machine learning model.

##Contributions
Contributions to this project are welcome! If you have any ideas for improvements or find any issues, feel free to open an issue or submit a pull request.

##License
This project is licensed under the MIT License.
