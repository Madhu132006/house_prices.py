# 🏠 House Price Prediction using Linear Regression
This project demonstrates a simple **Linear Regression** model to predict house prices based on features like area, number of bedrooms, and number of bathrooms. It's built using Python and Scikit-learn, with visualization using Matplotlib.
## 📁 Dataset
The model uses a CSV file named `house_prices.csv` containing the following columns:
* `area`: Size of the house (in sq. ft.)
* `bedrooms`: Number of bedrooms
* `bathrooms`: Number of bathrooms
* `price`: Actual price of the house (target variable)
> ⚠️ **Note**: Replace `'house_prices.csv'` with the actual path to your dataset if it's different.
## 🧠 Model Details
* **Algorithm**: Linear Regression
* **Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`
* **Evaluation Metric**: Root Mean Squared Error (RMSE)
## 📊 Output
* **RMSE** value for model evaluation.
* **Scatter Plot** comparing actual vs predicted prices.
![Sample Scatter Plot](preview.png)
## 🚀 Getting Started
1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction
   ```
2. **Install dependencies**
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```
3. **Run the script**
   ```bash
   python house_price_predictor.py
   ```
## 📌 To-Do
* Add more features (location, age of property, etc.)
* Use other models (Random Forest, XGBoost)
* Add model saving/loading with `joblib` or `pickle`
## 📜 License
This project is licensed under the MIT License. Feel free to use and modify!
