🏡 California House Price Prediction

This project focuses on predicting the median house prices in California using Linear Regression, a fundamental machine learning algorithm. It demonstrates how to analyze, preprocess, visualize, and model data to build a predictive system for real-world housing datasets.

📖 Introduction

The California Housing Price Prediction project aims to predict housing prices based on various socio-economic and geographic features such as:

Median income of residents

Average number of rooms

Population density

Latitude and longitude of the area

Ocean proximity and more

Accurately predicting housing prices can help:

Buyers understand market trends

Sellers set competitive prices

Real estate agents and investors identify profitable areas

This project serves as a step-by-step example of implementing a regression model, from data preprocessing to visualization, training, testing, and evaluation.

🎯 Project Objectives

Understand the relationship between housing features and prices.

Clean and preprocess raw data for modeling.

Build a Linear Regression model to predict house prices.

Evaluate the model’s accuracy and visualize its performance.

Provide insights into which features most influence housing prices.

📂 Dataset Information

The dataset used is the California Housing Dataset, containing details about various districts in California. Key columns include:

MedInc – Median income of households

HouseAge – Average age of houses

AveRooms – Average number of rooms per household

AveOccup – Average number of occupants per household

Latitude and Longitude – Geographical coordinates

MedHouseVal – Target variable (house price)

The dataset requires preprocessing to handle missing values and ensure all features are in a suitable format for modeling.

⚙️ Workflow of the Project

Data Collection
We load the California housing dataset using Pandas to explore and manipulate the data.

Data Cleaning & Preprocessing
Handle missing or null values in features.

Remove irrelevant or duplicate columns if any.

Normalize or scale numeric data if required.

Exploratory Data Analysis (EDA)
We use Matplotlib to:

Visualize distributions of housing prices and incomes.

Plot scatter graphs to study relationships between features like income vs. price.

Identify outliers or unusual patterns.

Data Splitting
Split the dataset into Training (80%) and Testing (20%) sets using train_test_split.

Model Building
Implement Linear Regression from Scikit-learn.

Fit the model on the training data to learn patterns.

Model Evaluation
Test the model on the unseen test data.

Evaluate performance using metrics like:

R² Score (goodness of fit)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Visualization of Results
Compare predicted vs. actual house prices.

Visualize residuals to identify errors in prediction.

🛠️ Technologies Used

Programming Language: Python 3.x

Libraries:

pandas – For data manipulation

numpy – For numerical computations

matplotlib – For visualization

scikit-learn – For machine learning model implementation

📊 Results & Insights

The Linear Regression model was able to predict house prices with reasonable accuracy.

Median income was found to be one of the strongest predictors of housing prices.

The model highlights how socio-economic and geographical factors influence real estate pricing.

Further improvements can be made by:

Trying more advanced models (e.g., Random Forest, Gradient Boosting)

Performing feature engineering

Normalizing skewed data distributions
