# Sales Predictor

This project aims to predict sales using machine learning techniques. The notebook demonstrates data preprocessing, exploration, and model implementation for regression tasks.

## Project Structure

- **Data**: The dataset includes files:
  - `train.csv`: Training data with sales and related features.
  - `stores.csv`: Information about the stores.
  - `features.csv`: Additional features impacting sales.
- **Notebook**: Contains all steps from data exploration to model evaluation.

## Workflow

1. **Data Loading**:
    - Loaded datasets using `pandas`.
    - Explored the structure and key statistics of the data.

2. **Data Preprocessing**:
    - Cleaned missing values and outliers.
    - Applied feature scaling using `MinMaxScaler`.

3. **Exploratory Data Analysis (EDA)**:
    - Visualized trends and relationships using `matplotlib` and `seaborn`.
    - Conducted statistical analysis with `scipy` and `statsmodels`.

4. **Model Training**:
    - Tested regression models including:
        - Linear Regression
        - Random Forest Regressor
        - K-Nearest Neighbors (KNN)
        - XGBoost Regressor

5. **Model Evaluation**:
    - Evaluated models using metrics like MAE, RMSE, and R².

## Dependencies

The following Python libraries are required:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `statsmodels`
- `sklearn`
- `xgboost`

## How to Use

1. Clone the repository and navigate to the project directory.
2. Ensure the required datasets (`train.csv`, `stores.csv`, `features.csv`) are available.
3. Open the notebook and execute cells sequentially to follow the analysis and predictions.

## Results

The notebook provides insights into the best-performing model for sales prediction, highlighting feature importance and model performance metrics.
