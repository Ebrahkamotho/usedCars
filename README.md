# *Used Cars Data EDA and ML Model.*
       This repository contains the code and data for an EDA (Exploratory Data Analysis) and
       ML (Machine Learning) model project based on a dataset of used cars.
       The goal of this project is to analyze the dataset and build a predictive model for car selling price based on various features.
       
 # *Dataset*
The dataset used in this project is a CSV file named cars.csv, which contains information on used cars, such as 
brand, model, age, kilometers driven, seller type, fuel type, transmission type, mileage, engine, max power, seats, and selling price.

# *EDA*
The EDA (Exploratory Data Analysis) process involves exploring and analyzing the dataset to gain insights and understanding of the data. 
The EDA process includes various steps, such as data cleaning, data visualization, and statistical analysis. 
In this project, we have performed the following EDA tasks:

1. Removed the Unnamed: 0 column as it was not useful for analysis.
2. Checked for missing values and handled them.
3. Identified categorical variables and checked their value counts.
4. Visualized the top and bottom 10 brands and models based on selling price.
5. Visualized the distribution of vehicle age, selling price, and mileage.
6. Created a box plot of selling price by brand and fuel type.
7. Created a stacked bar chart of fuel type by seller type.

# *ML Model*
The ML (Machine Learning) model is built to predict the selling price of used cars based on various features.
We have used the following steps to build the model:
- Performed feature engineering to create new features, such as vehicle_age and price_per_km
- Split the data into training and testing sets
- Trained and tested the model using linear regression and lasso algorithms.
- Evaluated the model's performance using various metrics, such as mean absolute error, mean squared error, and R-squared

# *Files*
The repository contains the following files:

- cars.csv: The original dataset
- cars_cleaned.csv: The cleaned dataset after handling missing values and feature engineering
- cars_eda.ipynb: The Jupyter notebook containing the EDA tasks and visualizations
- The Jupyter notebook containing the ML model building and evaluation tasks
- README.md: The readme file explaining the project and its contents

# *Conclusion*
In conclusion, this project involved exploring and analyzing a dataset of used cars and building a predictive ML model for car selling price.
The EDA process helped us to understand the dataset and identify patterns and trends, while the ML model helped us to make predictions based on the data.
The final model's performance can be improved further by fine-tuning the hyperparameters or trying different algorithms.
