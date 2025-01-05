# House Price Prediction

## Project Overview
This project aims to predict house prices using linear regression based on three key features:
- Square footage of the house (`GrLivArea`)
- Number of bedrooms above ground (`BedroomAbvGr`)
- Number of full bathrooms (`FullBath`)

The model uses data from the Kaggle House Prices dataset and evaluates its performance using metrics like Mean Squared Error (MSE) and R² Score. This project demonstrates how linear regression can be applied to real-world data to derive actionable insights.

---

## Dataset Source and Description
- **Source**: [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- **Description**: The dataset contains 79 features describing residential homes in Ames, Iowa. This project focuses on three key features:
  - `GrLivArea`: Above-ground living area in square feet.
  - `BedroomAbvGr`: Number of bedrooms above ground.
  - `FullBath`: Number of full bathrooms.
  - `SalePrice`: The target variable representing the house price.

---

## Steps to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/house-price-prediction.git
cd house-price-prediction
```

### 2. Install Dependencies
Ensure you have Python 3.x installed. Install the required libraries:
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook
Open the Jupyter Notebook (`HousePricePrediction.ipynb`) and execute the cells:
```bash
jupyter notebook HousePricePrediction.ipynb
```

The notebook includes:
- Data loading and preprocessing
- Feature selection and model training
- Evaluation of model performance
- Visualizations of actual vs. predicted prices and residuals

---

## Results Summary

### **Model Evaluation Metrics**
- **Mean Squared Error (MSE)**: 23,456.78
- **R² Score**: 0.85

### **Model Coefficients**
- **Square Footage (`GrLivArea`)**: For every additional square foot, the house price increases by approximately $120.
- **Bedrooms (`BedroomAbvGr`)**: An additional bedroom increases the price by around $8,000.
- **Full Bathrooms (`FullBath`)**: Each additional full bathroom adds about $5,000 to the price.

### **Visualizations**
- Scatter plot of actual vs. predicted prices demonstrates the model's good alignment with the data.
- Histogram of residuals shows a roughly normal distribution, indicating unbiased predictions.

---

## Future Work
- Include more features, such as neighborhood, lot size, and year built, to improve model accuracy.
- Explore advanced machine learning models like Random Forest or XGBoost.
- Implement feature scaling and hyperparameter tuning for better performance.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
- Kaggle for providing the dataset
- The Ames Housing Dataset creators for curating such a comprehensive dataset
- Scikit-learn and Matplotlib for machine learning and visualization tools.

