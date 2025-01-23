## Supply Chain
 This project aims to develop an AI-driven model for product-wise sales forecasting using the DataCo Smart Supply Chain dataset. The project aims to understand the structure and contents of the DataCo Smart Supply Chain dataset, perform data cleaning and preprocessing, conduct exploratory data analysis (EDA) to identify key features and patterns in the data, perform feature engineering, train, cross-validate and evaluate different models of regression and time series forecasting, and select the best performing model.

### Methods Used
- Outlier Analysis
- Correlation Analysis
- Data Preparation
- Principal Component Analysis (PCA)
- Variance Inflation Factor (VIF) Analysis
- Model Evaluation and Interpretation

### Technology Used
The project utilizes the following technologies and libraries:
 - Python: The primary programming language used for data analysis and modeling.
 - Pandas: A powerful library for data manipulation and analysis.
 - NumPy: A library for numerical operations.
 - Scikit-learn: A machine learning library used for model building, evaluation, and feature engineering.
 - XGBoost: A robust and efficient library for gradient boosting, used for predictive modeling.
 - ARIMA/Prophet/LSTM: Libraries and models used for time series forecasting.
 - Jupyter Notebook: An interactive environment for developing, presenting, and sharing data analysis workflows.


### Usage
 1. Open the Jupyter Notebook: `Jupyter Notebook`
 2. Run the analysis scripts in the provided order.
    - `1. EDA and Common Data Preparation.ipynb`
      This notebook contains all the steps necessary to clean and preprocess the data. It should be run first to ensure that the data is in the correct format for analysis.
      Ensure the prepared data is saved correctly.
    - `2. LinearRegression.ipynb`
      This notebook analyzes the prepared data. It should run after `1. EDA and Common Data Preparation.ipynb`.
    - `3. Tree Based Regression Models.ipynb`
      This notebook focuses on training machine learning models and tuning their hyperparameters. It includes model evaluation and selection to achieve the best performance. It should run after `2. LinearRegression.ipynb`.
    - `4. Time Series Based Models.ipynb`
      This notebook implements time series-based models for accurate sales forecasting using the DataCo Global Supply Chain dataset. This comes after `3. Tree Based Regression Models.ipynb`.
    -`5. Final Project.ipynb`
      This notebook is executed at the last of all the project files.


### License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.


