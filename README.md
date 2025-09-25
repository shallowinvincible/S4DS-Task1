📊 Regression Analysis on Combined Dataset (2017–2019)

This project performs Exploratory Data Analysis (EDA) and builds a Linear Regression Model to predict a target variable based on combined data from multiple years.
The main emphasis is on data cleaning, feature engineering, and visualization to ensure the dataset is ready for modeling.

📝 Project Overview

The goal of this project is to:

Merge datasets from 2017, 2018, and 2019 into one unified dataset.

Clean and preprocess the data with techniques such as null-value removal, column selection, and encoding.

Engineer a new feature: overall_rating_average to capture a more holistic metric.

Fit and evaluate a Linear Regression model on the processed data.

📂 Dataset

The project uses three separate datasets:

FIFA_2017.csv

FIFA_2018.csv

FIFA_2019.csv

These were merged to create a single dataset for analysis.

⚙️ Steps Performed
1️⃣ Data Merging

Combined data from 2017, 2018, and 2019 into a single DataFrame.

2️⃣ Data Cleaning

Removed null values where necessary.

Dropped irrelevant or unnecessary columns.

Extracted useful values from nested or formatted columns.

3️⃣ Feature Engineering

Created a new feature overall_rating_average (average of rating columns across years).

4️⃣ Encoding

Encoded categorical variables using Label Encoding / One-Hot Encoding to make them machine-readable.

5️⃣ Model Building

Split the data into train and test sets.

Fitted a Linear Regression model using scikit-learn.

6️⃣ Evaluation

Evaluated model performance using metrics like R² score, MAE, or RMSE.
