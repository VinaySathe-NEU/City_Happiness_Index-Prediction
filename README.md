# City_Happiness_Index-Prediction
The City Happiness Score Prediction notebook utilizes data science and machine learning to forecast happiness scores across various cities. By examining socio-economic, environmental, and other relevant factors, this project aspires to pinpoint key determinants of urban happiness, aiding city planners and stakeholders in enhancing quality of life.

# Abstract

The dataset provides a comprehensive overview of various urban quality-of-life metrics across different cities. It includes data on noise levels, traffic density, green space areas, air quality, cost of living, and healthcare quality.

The diverse set of indicators allows for multifaceted analyses of urban environments, examining how different factors contribute to the well-being of city dwellers.


# Variable Description

1. City: Name of the city being evaluated.
2. Month: Month when the data was collected.
3. Year: The year the data pertains to, all entries are for 2024.
4. Decibel_Level: Average noise level in the city, measured in decibels.
5. Traffic_Density: Qualitative assessment of traffic volume, categorized as * "High", "Medium", etc.

6. Green_Space_Area: Percentage of the city covered by parks and other green spaces.
7. Air_Quality_Index: Numerical index representing the air quality, with higher values indicating poorer quality.
8. Happiness_Score: A score reflecting the general happiness of the city's residents, on a presumed scale of 0-10.
9. Cost_of_Living_Index: An index reflecting the city's cost of living, with 100 used as a baseline reference.
10. Healthcare_Index: Numerical index indicating the quality of healthcare services available in the city.

**3 Column containing Categorical Data**('City', 'Month', 'Traffic_Density')

**7 Column containing Numerical Data**('Year', 'Decibel_Level', 'Green_Space_Area', 'Air_Quality_Index', 'Happiness_Score', 'Cost_of_Living_Index', 'Healthcare_Index')

1. Exploratory Data Analysis (EDA)

Conducted exploratory data analysis to understand the dataset's structure and characteristics, including variable distributions, missing values, and outliers.

2. Data Visualization

Created various visualizations such as histograms, scatter plots, and box plots to gain insights into the data and explore relationships between variables.

3. Data Preprocessing

Cleaned the dataset by handling missing values and outliers, and encoded categorical variables as necessary for machine learning.

4. Model Building

Built machine learning models using algorithms like Gradient Boosting, Random Forest, and Linear Regression to predict heart attack likelihood.

5. Hyperparameter Tuning

Performed hyperparameter tuning using techniques like GridSearchCV to optimize model performance.

6. Model Evaluation

Evaluated model performance using metrics such as RMSE, MSE, MAE, and R-squared, and visualized results for interpretation.

7. Statistical Analysis

Conducted statistical analysis, including the Variance Inflation Factor (VIF), to assess multicollinearity among independent variables.

8. Model Interpretability

Assessed the interpretability of models and their predictions in the context of the dataset.



## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the developers of the various Python libraries used in this project.
- Inspired by the need to simplify and automate the machine learning workflow.
