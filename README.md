# HexSoftwares_Project_California_Housing_Price_Prediction
Python | Data Analysis | Machine Learning | Linear Regression | Pandas | Scikit-learn
## Project Overview

This project analyzes the California Housing dataset and builds a machine learning model to predict housing prices based on demographic, geographic, and housing-related features.

The objective of the project is to explore relationships between housing characteristics and house prices and to develop a predictive model using machine learning techniques.

---

## Dataset

The dataset contains information about housing districts in California.
Each row represents a district and includes several features describing housing conditions and population characteristics.

### Main Features

* *Longitude* – Geographic coordinate of the district
* *Latitude* – Geographic coordinate of the district
* *Housing Median Age* – Median age of houses in the district
* *Total Rooms* – Total number of rooms in the district
* *Total Bedrooms* – Total number of bedrooms
* *Population* – Population living in the district
* *Households* – Number of households in the district
* *Median Income* – Median income of households
* *Median House Value* – Median price of houses (target variable)

---

## Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas and inspected using head() and tail() to understand the structure of the data.

### 2. Data Exploration

Initial exploration includes:

* Checking dataset dimensions
* Inspecting column names
* Understanding feature distributions

### 3. Data Cleaning

The dataset is checked for:

* Missing values
* Duplicate rows

This ensures the dataset is clean and suitable for analysis.

### 4. Exploratory Data Analysis (EDA)

Several visualizations are used to understand the relationships between variables:

* Scatter plot (Average Rooms vs House Price)
* Correlation heatmap
* Price distribution histogram
* Boxplot for outlier detection
* Geographic visualization of housing prices

These visualizations help identify key patterns and relationships in the data.

### 5. Feature Engineering

A new feature called *rooms_per_person* is created to represent the ratio of rooms available per person in a district.

### 6. Train-Test Split

The dataset is divided into training and testing sets to evaluate the model performance.

### 7. Model Training

A *Linear Regression model* is trained using the training dataset to predict housing prices.

### 8. Model Evaluation

The model performance is evaluated using:

* *Mean Squared Error (MSE)*
* *R² Score*

These metrics measure the accuracy of the predictions.

### 9. Prediction Visualization

A scatter plot comparing *actual vs predicted prices* is used to evaluate how well the model performs.

---

## Key Insights

* Median income has a strong relationship with housing prices.
* Geographic location influences housing value.
* Housing characteristics such as rooms and population density contribute to price variations.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

California_Housing_Price_Prediction
│
├── California_Housing_price.ipynb
├── California_Housing_Data.csv
└── README.md

---

## Conclusion

This project demonstrates how data analysis and machine learning techniques can be applied to understand housing market patterns and predict house prices based on multiple factors.

The Linear Regression model provides useful insights into the relationship between housing features and property values in California.
