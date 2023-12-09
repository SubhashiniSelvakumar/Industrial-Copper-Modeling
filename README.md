# Industrial-Copper-Modeling
# Industrial Copper Modeling Application

## Overview

This repository contains the code for an Industrial Copper Modeling Application. The application is built using Streamlit and incorporates two machine learning models: one for predicting selling prices and another for predicting the status of industrial copper transactions.

## Features

- **Predict Selling Price:**
  - Users can input various parameters, such as status, item type, country, application, product reference, quantity tons, thickness, width, and customer ID.
  - The application uses a regression model to predict the selling price based on the provided input.

- **Predict Status:**
  - Users can input parameters including quantity tons, thickness, width, customer ID, selling price, item type, country, application, and product reference.
  - The application uses a classification model to predict the status (Won or Lost) based on the provided input.

## Models and Transformers

The trained regression model, transformers (scaler, one-hot encoder), and the trained classification model are saved in the repository.
These models are loaded during runtime for making predictions.

## Data
The application uses a CSV file (Copper_Set.csv) containing historical data for training the machine learning models.
