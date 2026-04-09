# analysis.py

Crop Recommendation Data Analysis using Python
Project Description

This project focuses on performing an end-to-end data analysis on a crop recommendation dataset using Python. The objective is to explore how different soil nutrients (Nitrogen, Phosphorus, Potassium) and environmental factors (temperature, humidity, pH, rainfall) influence crop suitability.

The dataset has been taken from Kaggle
 and contains structured agricultural data that can be used for analysis as well as machine learning applications.

Objectives
To understand the distribution of soil and environmental variables
To identify relationships between different features
To perform Exploratory Data Analysis (EDA)
To visualize patterns using graphs and plots
To apply regression modeling to study variable relationships
To derive meaningful insights for crop recommendation
# Tools & Technologies Used
Python
Pandas (Data Handling)
NumPy (Numerical Computation)
Matplotlib & Seaborn (Visualization)
Scikit-learn (Regression Modeling)
📊 Dataset Details

The dataset includes the following features:

N – Nitrogen content in soil
P – Phosphorus content in soil
K – Potassium content in soil
Temperature – Average temperature
Humidity – Relative humidity
pH – Soil pH value
Rainfall – Annual rainfall (mm)
Label – Crop type
Total Observations: 2200
Number of Crops: 22 (balanced dataset)
🔍 Data Analysis Process
1. Data Cleaning
Checked for missing values and duplicates
Cleaned dataset to ensure consistency
Verified data types
2. Exploratory Data Analysis (EDA)
Used summary statistics (mean, median, mode)
Analyzed distribution using histograms and boxplots
Observed variability in nutrient levels and environmental factors
3. Data Visualization
Histograms to study distribution
Boxplots to detect outliers
Scatter plots to analyze relationships
Heatmap to visualize correlations
4. Correlation Analysis
Identified strong positive relationship between:
Phosphorus (P) and Potassium (K)
Found weak relationships between:
Temperature and rainfall
pH and temperature
5. Regression Modeling
Applied Simple Linear Regression to predict Potassium using Phosphorus
Built Multiple Linear Regression model using multiple variables
Evaluated model performance using R² score
 Key Insights
The dataset is highly structured and balanced, making it ideal for analysis
Different crops require specific combinations of nutrients and climate conditions
Strong clustering indicates clear separation between crop types
Environmental factors like rainfall and temperature are relatively independent
Soil nutrients (especially P and K) show strong relationships
# Applications
Crop recommendation systems
Precision agriculture
Soil and fertilizer management
Climate-based farming decisions
Machine learning model development
Conclusion

This project demonstrates that crop suitability depends on a combination of soil nutrients and environmental conditions rather than a single factor. The insights derived can be used to build intelligent systems for smart agriculture and crop prediction.

Future Scope
Build classification model for crop prediction
Deploy as a web application
Integrate real-time weather data
Improve model accuracy using advanced ML algorithms

Author

Tashwita Kanse
