# Classification-Customer-Churn

This project focuses on predicting customer churn using machine learning. The dataset and code included help train a model to identify customers who are likely to leave a service.

## Project Structure

- **Churn_Modelling.csv**: This is the dataset used for training the model. It contains customer data including demographics, account information, and whether the customer has churned.
- **app.py**: The main application file. This file contains the code to run the model, including preprocessing steps and predictions.
- **model.h5**: This is the trained machine learning model in HDF5 format, which is used to predict churn.
- **Label_Encoder_Gender.pkl**: A pickle file containing the label encoder for the 'Gender' feature.
- **onehot_encoder_geo.pkl**: A pickle file containing the one-hot encoder for the 'Geography' feature.
- **scaler.pkl**: A pickle file containing the scaler used for feature scaling.
- **requirements.txt**: Contains the list of dependencies and libraries required to run the project.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/churn-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd churn-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application locally:
   ```bash
   streamlit run app.py
   ```

## Web Application

You can also access the web version of this application hosted on Streamlit by clicking the following link:

[Customer Churn Prediction Web App](https://ann-classification-customer-churn-a9cutfyvfxgt8gxebeeuvq.streamlit.app/)

## Dataset

The dataset (`Churn_Modelling.csv`) includes the following key features:

- **CustomerID**: Unique identifier for each customer.
- **Geography**: The country from which the customer belongs.
- **Gender**: The gender of the customer.
- **Age**: The age of the customer.
- **Tenure**: The number of years the customer has been with the company.
- **Balance**: The account balance of the customer.
- **Exited**: Indicates whether the customer has churned (1) or not (0).

## Model

The model is a deep learning neural network saved in `model.h5`. It uses multiple features such as geography, gender, age, balance, and tenure to predict whether a customer will churn.

## Usage

After running `app.py`, the model will load, preprocess the data, and predict churn for new customer data.

