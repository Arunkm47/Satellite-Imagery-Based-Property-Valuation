# 🏠 House Price Prediction using ML & Satellite Images

## Overview
This project predicts house prices using structured housing data and geographical information. Satellite images are fetched using Google Maps Static API to enable future multimodal learning.

## Project Structure

.
├── data/
│   └── images/
│       ├── train/
│       └── test/
├── preprocessing.py
├── image_fetcher.py
├── train_models.py
├── X_train.npy
├── X_valid.npy
├── y_train.npy
├── y_valid.npy
├── X_test.npy
├── house_price_predictions.csv
└── README.md

## Satellite Image Fetching

Images are downloaded using Google Maps Static API based on latitude and longitude.

### Configuration
- Image size: 256x256
- Zoom level: 18
- Map type: Satellite

## Data Preprocessing
- Median imputation for missing values
- Standard scaling of numerical features
- Train-validation split

## Models Used
- PyTorch Neural Network
- XGBoost Regressor

## Evaluation Metrics
- RMSE
- R² Score

