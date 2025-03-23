# House Price Prediction

## Overview
This project is a **House Price Prediction** model that estimates house prices based on input features such as square footage, number of bedrooms, and number of bathrooms. The model is implemented using **Streamlit** for the user interface and utilizes a pre-trained machine learning model stored as a `.pkl` file.

## Features
- User-friendly web interface using **Streamlit**
- Takes user input for house features
- Predicts house prices based on a trained model
- Displays the predicted price instantly

## Technologies Used
- **Python**
- **Streamlit** (for UI)
- **Joblib** (for loading the trained model)
- **Pandas & NumPy** (for data processing)

## Installation and Setup

### Prerequisites
Ensure you have **Python 3.7+** installed along with the following dependencies:
```bash
pip install streamlit joblib numpy pandas
```

### Running the Application
1. Clone the repository or download the project files.
2. Ensure the trained model (`model.pkl`) is present in the specified location.
3. Run the application using the following command:
```bash
streamlit run app.py
```
4. Open the browser and interact with the web application.

## Project Files
- `app.py`: Streamlit application file for user interaction
- `model.pkl`: Pre-trained machine learning model
- `aera vs price.ipynb`: Jupyter Notebook for data analysis and model training

## How it Works
1. The user inputs the square footage, number of bedrooms, and number of bathrooms.
2. The application passes the input to the trained model.
3. The model predicts the house price and displays it on the UI.

## Output
After entering values for **Square Footage, Bedrooms, and Bathrooms**, the app predicts and displays the house price. Example output:
```
The predicted house price is: $250,000
```

## Conclusion
This project provides a simple yet effective solution for predicting house prices using machine learning. With an easy-to-use web interface and a trained model, users can quickly estimate house prices based on key features. Future enhancements can further improve prediction accuracy and usability.


