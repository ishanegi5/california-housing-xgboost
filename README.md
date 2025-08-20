# California Housing Price Prediction using XGBoost

This project predicts the **median house value** in California districts using the **California Housing dataset**. The model is built with **XGBoost Regressor** and evaluated with common regression metrics.

## 📊 Dataset
- Source: `from sklearn.datasets import fetch_california_housing`
- Samples: ~20,640
- Features: 8 numeric attributes such as:
  - MedInc (median income in block)
  - HouseAge
  - AveRooms
  - AveBedrms
  - Population
  - AveOccup
  - Latitude
  - Longitude
- Target: Median house value (in 100,000 USD)

## 🛠️ Tech Stack
- Python
- Pandas, NumPy (data handling)
- Scikit-learn (train/test split, metrics)
- XGBoost (model training)
- Matplotlib/Seaborn (optional visualization)

## ⚙️ Steps
1. Load dataset with `fetch_california_housing()`
2. Split into training and testing sets
3. Train **XGBoostRegressor**
4. Evaluate with R², RMSE, and MAE

## 📈 Results
- **R² Score:** ~0.84  
- **Root Mean Squared Error (RMSE):** ~0.456  
- **Mean Absolute Error (MAE):** ~0.303  

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/ishanegi5/california-housing-xgboost.git
cd california-housing-xgboost

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook California_Housing_XGBoost.ipynb

📌 Requirements
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn

📢 License

This project is open-source and available under the MIT License.

🔗 Author: Isha Negi
