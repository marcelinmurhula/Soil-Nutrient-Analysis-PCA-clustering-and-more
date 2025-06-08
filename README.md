
Copier le code
# Soil Nutrient Data Analysis and Modeling Project

## Overview

This project involves analyzing soil nutrient data to assess soil quality and efficiency across various districts in the south-kivu province, in DRC. The main objectives include:

- **Exploratory Data Analysis (EDA):** Understand the distribution and relationships between soil nutrients such as pH, organic matter, nitrogen, phosphorus, and potassium.
- **Principal Component Analysis (PCA):** Reduce the dimensionality of the dataset and visualize the principal components.
- **Clustering:** Apply K-means clustering to categorize districts based on soil nutrient data.
- **Regression Modeling:** Predict nitrogen content using features such as pH level and organic matter percentage.
- **Efficiency Analysis:** Evaluate the efficiency of nitrogen, phosphorus, and potassium utilization across different districts.

## Dataset

The dataset used in this project contains soil nutrient data with the following columns:

- **District:** Name of the district.
- **Soil Type:** Type of soil in the district.
- **pH Level:** Soil pH level.
- **Organic Matter (%):** Percentage of organic matter in the soil.
- **Nitrogen Content (kg/ha):** Amount of nitrogen in the soil.
- **Phosphorus Content (kg/ha):** Amount of phosphorus in the soil.
- **Potassium Content (kg/ha):** Amount of potassium in the soil.
## Data Analysis and Modeling

- **Exploratory Data Analysis (EDA):** EDA involves visualizing and understanding the data distribution and relationships between variables.
- **Principal Component Analysis (PCA):** PCA is used to reduce the dimensionality of the dataset and visualize the principal components.
- **Clustering:** K-means clustering is applied to categorize districts based on soil nutrient data.
- **Regression Modeling:** A RandomForestRegressor model predicts nitrogen content based on pH level and organic matter percentage.
- **Efficiency Analysis:** Calculate and analyze the efficiency of nitrogen, phosphorus, and potassium utilization across different districts.

## Results

- **PCA:** The first two principal components capture the most variance in the data, aiding in visualizing data patterns.
- **Clustering:** Clustering provides insights into distinct groups of districts based on soil nutrient profiles.
- **Regression:** The RandomForestRegressor model predicts nitrogen content with a mean squared error of 26.06.
- **Efficiency:** Soil nutrient efficiencies vary across districts, highlighting areas for potential improvement.

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- **Data source:** [Kaggle]
- **Libraries:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
