# Car Price Prediction using Regression Models

## Overview
This project aims to build a predictive model to estimate car prices based on various features such as brand, model, year, engine capacity, mileage, and more. The project involves Exploratory Data Analysis (EDA), data preprocessing, and multiple regression models to achieve accurate predictions.

## Features
- **Data Preprocessing:** Handling missing values, feature engineering, and scaling numerical variables.
- **Regression Models Implemented:**
  - Linear Regression
  - Decision Tree Regression
  - Random Forest Regression
  - Gradient Boosting Regression
  - Support Vector Regressor (SVR)
- **Hyperparameter Tuning:** GridSearchCV for model optimization.
- **Evaluation Metrics:** R² score, Mean Absolute Error (MAE), Mean Squared Error (MSE), RMSE.

## Dataset
The dataset contains information about various car listings, including:
- Brand & Model
- Manufacturing Year
- Engine Size
- Mileage
- Fuel Type
- Transmission Type
- Price (Target Variable)

## Installation
Clone the repository and install dependencies:
```bash
$ git clone https://github.com/your-username/car-price-prediction.git
$ cd car-price-prediction
$ pip install -r requirements.txt
```

## Usage
Run the main script to train and evaluate models:
```bash
$ python main.py
```

## Results
- Model performances are evaluated based on R² score and error metrics.
- Random Forest and Gradient Boosting models showed the best accuracy.
- SVR requires careful tuning for optimal results.

## Future Enhancements
- Feature selection techniques to improve performance.
- Deployment using Flask/Django.
- Integration with a web interface for user-friendly predictions.

## Contributing
Contributions are welcome! Feel free to fork, submit issues, or create pull requests.

## License
MIT License

## Author
Abdul Basith


