# Eda-on-Rainfall-and-Crop-Production-Data
This report presents an exploratory data analysis (EDA) on a dataset that examines the relationship between rainfall and agricultural production. The goal of the analysis is to uncover patterns, detect outliers, and explore the correlation between rainfall, crop yield, production, and area cultivated. The data contains variables such as rainfall, area in hectares, production in tons, and yield (tons per hectare).

# Dataset Description
The dataset contains the following key features:

- rainfall: The amount of rainfall in millimeters.
- Area_in_hectares: The area of land used for cultivation.
- Production_in_tons: Total crop production in tons.
- Yield_ton_per_hec: The crop yield in tons per hectare.

# Data Exploration
Basic Data Information

The dataset summary is provided below using .info(), which gives a snapshot of data types, null values, and column names. The summary statistics from .describe() helped understand the distribution of the numeric columns.

# Univariate Analysis
Rainfall Analysis

A histogram was plotted to visualize the distribution of rainfall. It shows the frequency of different rainfall ranges:

# Bivariate Analysis
Relationship Between Rainfall and Yield

A scatterplot was created to visualize the relationship between rainfall and yield per hectare. There appears to be a moderate positive correlation

# Outlier Detection

Outliers in rainfall were identified using the Z-score method, where Z-scores greater than 3 or less than -3 were considered outliers. 

# Correlation Analysis

A heatmap of the correlation matrix was generated to analyze relationships between rainfall, area, production, and yield. The heatmap shows positive and negative correlations


