# PRODIGY_ML_01

# House Price Prediction Project


## Overview
This project aims to predict house prices using machine learning techniques. The dataset used for this project includes various features such as square footage, number of bedrooms, number of bathrooms, and other relevant attributes that can influence house prices.

## Project Structure

The project is structured as follows:

- Data Loading and Exploration: 
  - Loaded the dataset (`train.csv`) containing house price data.
  - Explored the dataset to understand its structure, features, and distributions.
  
- Data Preprocessing:
  - Cleaned the dataset by handling missing values and outliers.
  - Performed feature engineering to extract relevant features for model training.
  
- Model Development:
  - Built a Linear Regression model to predict house prices.
  - Evaluated the model using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.
  
- Model Deployment:
  - Deployed the trained model to make predictions on new data (`test.csv`).
  - Generated a submission file (`submission.csv`) for competition or evaluation purposes.
  
- Visualization:
  - Created visualizations such as scatter plots, regression plots, and residual plots to analyze model performance and data relationships.

## Technologies Used
- Python
- Jupyter Notebook
- Libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Files Included
- `train.csv`: Training dataset containing house price data.
- `test.csv`: Test dataset for making predictions.
- `data_description.txt`: Description of each column in the dataset.
- `sample_submission.csv`: Template for submitting predictions.

## Usage
1. Clone Repository: Clone this repository to your local machine.
   ```
   git clone https://github.com/your_username/PRODIGY_ML_01.git
   ```
   
2. Setup Environment: Install the required libraries mentioned in `requirements.txt`.
   ```
   pip install -r requirements.txt
   ```
   
3. Run Jupyter Notebook: Open and run the Jupyter Notebook `house_price_prediction.ipynb`.
   ```
   jupyter notebook house_price_prediction.ipynb
   ```
   
4. Explore and Execute: Follow the instructions in the notebook to explore the data, preprocess it, train the model, and make predictions.

