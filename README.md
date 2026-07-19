# California House Price Prediction using XGBoost

## Overview

This project predicts California house prices using the XGBoost Regressor algorithm. It utilizes demographic, geographic, and housing-related features to estimate the median house value of a district.

The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction using machine learning.

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Data visualization
- Train-Test Split
- House price prediction using XGBoost Regressor
- Model evaluation using R² Score and MAE
- Predict house prices for new input values

---

## Dataset

The project uses the **California Housing Dataset**.

### Features

| Feature | Description |
|----------|-------------|
| MedInc | Median income of households |
| HouseAge | Median age of houses |
| AveRooms | Average number of rooms |
| AveBedrms | Average number of bedrooms |
| Population | Population of the block |
| AveOccup | Average house occupancy |
| Latitude | Latitude coordinate |
| Longitude | Longitude coordinate |

### Target Variable

- **Price** – Median house value

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook / Google Colab

---

## Machine Learning Workflow

1. Load Dataset
2. Data Exploration
3. Data Cleaning
4. Feature Selection
5. Data Visualization
6. Train-Test Split
7. Model Training (XGBoost Regressor)
8. Model Evaluation
9. House Price Prediction

---

## Model Performance

### Training Performance

- **R² Score:** 0.9472
- **Mean Absolute Error (MAE):** 0.1889

### Testing Performance

- **R² Score:** 0.8371
- **Mean Absolute Error (MAE):** 0.3079

The model explains approximately **84% of the variance** in house prices on unseen test data, demonstrating good predictive performance.

---

## Visualizations

The project includes:

- Correlation Heatmap
- Feature Distribution
- Scatter Plots
- Actual vs Predicted Price Plot
- Feature Importance Plot
- Boxplots for Outlier Detection

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/california-house-price-prediction.git
```

Navigate to the project directory:

```bash
cd california-house-price-prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook or Python script.

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Cross-validation for robust evaluation
- Feature engineering
- Deploy as a Flask or Streamlit web application
- Save and load trained models using Joblib
- Add an interactive user interface for predictions

---

## Author

**Ali Rizvi**

Software Engineer | Machine Learning Enthusiast

---

## License

This project is intended for educational and academic purposes. You are free to use and modify it with proper attribution.
