# Smart-Watch-Analysis
*Smart Watch Analysis and Data Visualization*

This project analyzes and visualizes data related to smartwatches, focusing on important features such as display size, water resistance, battery life, and price. The analysis includes calculating basic statistics, generating insightful visualizations, and exploring relationships between these features for different smartwatch brands.

*Key Features of the Analysis:*
*Data Preprocessing:*
Cleaning the dataset (if necessary).
Ensuring columns like Price (USD), Battery Life (days), Display Size (inches), and Water Resistance (meters) are numeric.

*Exploratory Data Analysis (EDA):*
Scatter Plots: 
Visualizing the relationship between price and battery life for various smartwatch brands.
Bar Charts: 
Comparing the total price and total battery life across different brands.
Descriptive Statistics: 
Calculating the average and standard deviation of features like display size, battery life, and price.

*Visualization Techniques:*
Seaborn Scatter Plot: 
Displays the relationship between Price (USD) and Battery Life (days) for different brands using a color hue to differentiate the brands.
Bar Plots: 
Summarizes the data by showing total price and total battery life for each brand.

*Statistical Analysis:*
Mean and standard deviation of columns such as display size, water resistance, battery life, and price.

*Visualizations and Insights:*
Scatter Plot: Highlights how price correlates with battery life, helping to understand whether higher-priced smartwatches provide longer battery life.
Bar Charts: Provides a comparison of total price and total battery life across various brands, revealing which brands offer more value or longer-lasting products.
Possible Enhancements:
Correlation Matrix: Add a heatmap to show correlations between the various features.
Linear Regression: Implement a basic regression model to predict battery life based on other features like price and display size.

*Conclusion:*
The analysis of smartwatch data reveals varying relationships between price and battery life across different brands, with no clear correlation between higher price and longer battery life. Some brands offer better value in terms of battery life at lower prices, while others focus on premium pricing with additional features. The bar charts and statistical metrics highlight significant differences in feature offerings between brands. Overall, the analysis provides insights into brand strategies and suggests potential for further exploration through predictive modeling.

*Dependencies:*
Python 3.x
pandas
numpy
matplotlib
seaborn
