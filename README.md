# Predicting Falcon 9 First Stage Landing Success

## Executive Summary:

- **Goal:** Predicting Falcon 9 first stage landing success to estimate launch costs and inform competitive bidding.
- **Methodology:** Data collection (API calls and web scraping), data wrangling, EDA (visualization and SQL), interactive visual analytics (Folium and Plotly Dash), and predictive analysis (classification models).
- **Key Finding:** Logistic Regression emerged as the best-performing model for predicting landing success.

## Introduction:

- **Context:** The commercial space industry and SpaceX's dominance through reusable rockets.
- **Importance:** Predicting Falcon 9 first stage landing success for competitive bidding, risk assessment, and technological advancement.
- **Objective:** Developing a reliable model for predicting landing success.

## Methodology:

### Data Collection:
- SpaceX REST API and web scraping for comprehensive launch data.
- JSON normalization, data enrichment through additional API calls, data filtering, and handling null values.

### EDA with Data Visualization:
- Categorical scatter plots, bar charts, and line charts to explore relationships between flight number, payload mass, orbit type, year, and landing success.

### EDA with SQL:
- Ten SQL queries performed on the dataset to uncover patterns related to launch sites, payload mass, booster versions, and landing outcomes.

### Build an Interactive Map with Folium:
- Interactive map using Folium to visualize launch site locations, highlighting NASA JSC with circles and markers.

### Build a Dashboard with Plotly Dash:
- Interactive dashboard using Plotly and Dash, featuring a pie chart for success rate visualization and a scatter chart for exploring payload mass and launch outcome correlations.

### Predictive Analysis (Classification):
- Building and evaluating classification models: data loading, preprocessing, splitting, model selection (Logistic Regression, SVM, Decision Tree, KNN), hyperparameter tuning, and model evaluation using accuracy and confusion matrices.
- Logistic Regression identified as the best-performing model based on its accuracy on the test data.

## Results:

- Visualizations and tables generated during the EDA process, showcasing trends and patterns in the data.
- Screenshots of the interactive Folium map and Plotly Dash dashboard, demonstrating their functionality and insights.
- Classification accuracy of the different models and the confusion matrix for the best-performing model (Logistic Regression).

## Conclusion:

- Summary of the project's findings and the identification of Logistic Regression as the best model for predicting Falcon 9 first stage landing success.
- Implications for the commercial space industry and potential future research directions.

## Appendix:

- Link to the GitHub repository containing the project's code, datasets, and other relevant materials.
