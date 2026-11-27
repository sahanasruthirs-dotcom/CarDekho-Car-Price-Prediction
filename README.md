# CarDekho Used Car Price Prediction

A machine learning regression project that estimates the selling price of a used car from its features.

## Overview
Using the CarDekho used-car dataset, the project cleans and explores the data, builds regression models, and predicts a car's selling price from inputs such as age, kilometers driven, fuel type, seller type, transmission and number of previous owners.

## Technologies Used
- Python
- Pandas and NumPy: data handling
- Matplotlib and Seaborn: visualization
- Scikit-learn: regression models and evaluation
- Jupyter Notebook / Google Colab

## Dataset
CarDekho used-car dataset.

| Feature | Description |
|---|---|
| Car_Name | Name and model of the car |
| Year | Manufacturing year |
| Selling_Price | Price the car was sold at (target) |
| Present_Price | Current showroom price |
| Kms_Driven | Distance travelled |
| Fuel_Type | Petrol, Diesel, CNG |
| Seller_Type | Individual or Dealer |
| Transmission | Manual or Automatic |
| Owner | Number of previous owners |

## Implementation Details
1. **Data preprocessing:** handle missing values and duplicates, encode categorical columns.
2. **Exploratory analysis:** visualize price distributions and relationships between features and price.
3. **Feature engineering:** derive features such as car age from the manufacturing year.
4. **Model building:** train regression models (Linear Regression, Decision Tree Regressor, Random Forest Regressor).
5. **Evaluation:** compare models using MAE, MSE, RMSE and R² score.
6. **Prediction:** estimate the selling price for new car details.

## Results
The notebook compares the models using MAE, MSE, RMSE and R² on a held-out test set, and plots actual against predicted prices.

## Project Structure
```
CarDekho-Car-Price-Prediction/
├── CarDekho project.ipynb   # Analysis, modeling and prediction
├── car_prediko.html         # HTML page for the project
├── requirements.txt
└── README.md
```

## Setup Instructions
```bash
git clone https://github.com/sahanasruthirs-dotcom/CarDekho-Car-Price-Prediction.git
cd CarDekho-Car-Price-Prediction
pip install -r requirements.txt
```

## Usage
1. Run `jupyter notebook` and open `CarDekho project.ipynb`.
2. Make sure the dataset CSV path in the first cells is correct.
3. Run all cells to train the models and see the evaluation and predictions.

## Future Improvements
- Hyperparameter tuning and ensemble models
- A Flask or Streamlit app for entering car details and viewing the predicted price
- Larger and more recent market data

## Author
**Sahana Sruthi R.S.** · B.Tech CSE (AI & Data Analytics)
[LinkedIn](https://www.linkedin.com/in/sahana-sruthi-r-s-4612b4315) · [Portfolio](https://sahanasruthirs-dotcom.github.io)
