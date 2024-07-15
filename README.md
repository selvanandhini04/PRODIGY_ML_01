House Price Prediction using Linear Regression
This project demonstrates the use of a linear regression model to predict house prices based on various features. The notebook includes data preprocessing, model training, evaluation, and prediction steps.

Contents
Task_1_House_Price_Prediction_Linear_Regression.ipynb: Jupyter notebook containing the code for the project.
predictions.csv: CSV file containing the predicted house prices for the test set.
Requirements
Python 3.x
Jupyter Notebook
pandas
numpy
matplotlib
seaborn
scikit-learn
You can install the required packages using the following command:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn
Data
The dataset used for this project is the House Prices dataset from Kaggle. It contains various features about houses, such as the number of bedrooms, the size of the lot, the year built, etc.

Notebook Overview
1. Import Libraries
The necessary libraries for data manipulation, visualization, and model building are imported.

2. Load Data
The training and test datasets are loaded using pandas.

3. Data Exploration
Exploratory Data Analysis (EDA) is performed to understand the distribution and relationship of features with the target variable (house prices).

4. Data Preprocessing
Data cleaning and preprocessing steps are applied, including handling missing values and encoding categorical variables.

5. Model Training
A linear regression model is trained on the preprocessed training data.

6. Model Evaluation
The performance of the model is evaluated using Mean Squared Error (MSE) and R-squared (R²) score.

7. Prediction
The trained model is used to predict house prices on the test set. The predictions are saved to a CSV file.

How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/house-price-prediction.git
Navigate to the project directory:
bash
Copy code
cd house-price-prediction
Open the Jupyter notebook:
bash
Copy code
jupyter notebook Task_1_House_Price_Prediction_Linear_Regression.ipynb
Run the notebook cells to execute the code.
Results
The notebook outputs the Mean Squared Error (MSE) and R-squared (R²) score for the model. The predictions for the test set are saved to predictions.csv.


