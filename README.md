# 🏡 House Price Prediction

This project is a machine learning-based solution to predict house prices using various features such as location, number of rooms, median income, and more. It includes end-to-end steps from data cleaning to feature engineering, model training, and evaluation.

## 📊 Project Highlights

- Performed **Exploratory Data Analysis (EDA)** to uncover trends and insights.
- Implemented **Feature Engineering** including One-Hot Encoding for categorical data.
- Trained and evaluated models using performance metrics.
- Applied various regression algorithms to compare results and select the best-performing model.

## 🔍 Key Techniques

### 🔧 Feature Engineering
- **One-Hot Encoding**: Used for categorical features like `ocean_proximity` which don't have any intrinsic order.
- **Avoided Label Encoding** to prevent introducing unintended ordinal relationships.

### 📈 Exploratory Data Analysis (EDA)
- Correlation matrix to identify relationships between variables.
- Visualizations to explore geographical data distribution and housing trends.

## 🛠️ Tools and Libraries

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🧠 ML Models

Models used :
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGB regressior(best for my dataset)

📈 Model Evaluation

 Used metrics like:
-Mean Absolute Error (MAE)
-Root Mean Squared Error (RMSE)
-R² Score
