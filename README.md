# US Housing Market Analysis and Rent Prediction

This project involves an in-depth analysis of housing market trends using the Zillow Home Value Index (ZHVI) and predictive modeling of rental prices using machine learning techniques. The primary objectives of this project are to analyze housing price trends across different price tiers and states, and to develop a predictive model for forecasting rental prices.

## Project Structure
- **Data Sources:**
  - `home_values.parquet`: Contains historical home value data categorized into bottom, mid, and top price tiers.
  - `rentals.parquet`: Includes historical rental price data with seasonal adjustments.

- **Data Analysis:**
  - Conducted exploratory data analysis (EDA) on home values and rental datasets.
  - Cleaned and preprocessed the data by handling missing values and structuring datasets for analysis.
  - Visualized trends in housing prices over time and across different U.S. states.

- **Modeling:**
  - Built a Random Forest Regressor model to forecast rental prices.
  - Performed hyperparameter tuning using GridSearchCV to enhance model performance.
  - Achieved a high R² score of ~0.95, demonstrating strong predictive power.

- **Tools & Process:**
  - Tools: Python, Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn
  - Process: Data cleaning, exploratory data analysis, model building, hyperparameter tuning, and performance evaluation.

- **Diagrams:**
  - **Entity-Relationship (ER) Diagram:** Provides a conceptual overview of data entities and their relationships.
  - **UML Diagram:** Visualizes the data model structure and dependencies for the home values dataset.

## Key Insights
- **Housing Market Trends:**
  - Overall upward trend in housing prices, with significant fluctuations in the top tier.
  - Notable price differences among states, with California and Hawaii showing the highest variability.

- **Rent Prediction Model:**
  - The model explains 95.42% of the variance in rent values.
  - Shows strong performance for most predictions, though struggles with extreme high-end rental prices.

## How to Run
1. **Install Required Libraries:**
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. **Run the Jupyter Notebook:**
- Open the notebook and execute cells sequentially to reproduce the analysis and modeling steps.

## Future Improvements
- Implement advanced feature engineering to improve high-end rent prediction.
- Explore additional models, such as Gradient Boosting or XGBoost, to enhance prediction accuracy.

## Author
Sherry Zhang

