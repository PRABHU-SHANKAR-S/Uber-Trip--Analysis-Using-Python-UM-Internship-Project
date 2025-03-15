# Uber-Trip--Analysis-Using-Python-Internship-Project


[Uber-Trip-Analysis-Using-Python-UM-Internship-Project](file:///C:/Users/Prabhushankar/OneDrive/Desktop/Uber%20Trip%20Analysis%20Project/Uber%20Trip%20Analysis%20Using%20Python.html)  
This project involves analyzing Uber trip data from New York City (2014–2015) to uncover trends, predict demand, and evaluate supply chain metrics. The analysis employs advanced data processing, visualization techniques, and machine learning models.

### Data Access and References  
Some of the large files used in this project have not been included in the repository due to size constraints. You can download the datasets from the links below:  

1. [Uber Trips Forecasting Using Machine Learning](https://www.kaggle.com/code/jbasurtod/uber-trips-forecasting-using-machine-learning/notebook)  
2. [Uber: Analyzing Uber Trips](https://www.kaggle.com/code/hillaryjude/uber-analyzing-uber-trips)  

For more details on data cleaning, EDA, and advanced analysis, refer to these resources.

---

## Key Features of the Project

### 1. Data Processing
- Performed data cleaning: handled duplicate and null values, and replaced missing data.
- Converted date columns into appropriate datetime formats for time-series analysis.
- Conducted exploratory data analysis (EDA) using Python libraries (pandas, seaborn, matplotlib).

### 2. Visualizations and Calculations
- Created insightful visualizations:
  - **Line, Bar, Scatter, Box Plots, Heatmaps, and Pivot Tables** to explore trends.
- Analyzed key metrics:
  - **Total Number of Trips for Each Base**.
  - **Monthly Trend of Trips** using Pickup Dates.

### 3. Machine Learning Models
- Built predictive models to forecast trip demand:
  - **Random Forest**: MAPE = 6.92%.
  - **Gradient Boosted Tree Regressor (GBTR)**: MAPE = 7.26%.
  - **Ensemble Model**: MAPE = 6.90%.
- The ensemble approach integrated XGBoost, Random Forest, and GBTR, leveraging their strengths for robust predictions.

---

## Insights & Conclusions

### Model Performance:
- **Random Forest** effectively captured temporal variations with good accuracy (6.92% MAPE).
- **GBTR** showed reasonable performance with a 7.26% MAPE.
- **Ensemble Model** was the best-performing model (6.90% MAPE), providing stable and reliable predictions.

### Impact of Window-Based Logic:
- Enhanced predictive accuracy by capturing seasonality and trends, critical for time-series forecasting.
- Reduced overfitting risks through cross-validation and parameter tuning.

### Practical Implications:
- **XGBoost** is ideal for scenarios demanding the lowest prediction error.
- **Ensemble Models** offer better stability and reliability, suitable for dynamic environments like ride-sharing demand.

---

## Tools & Technologies Used
- **Languages**: Python.
- **Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn, xgboost.
- **Techniques**: EDA, feature engineering, cross-validation, parameter tuning.
- **Visualization**: Line, bar, scatter, box plots, pivot tables, and heatmaps.

---

## Additional Analysis: Supply Chain Metrics
- Created dashboards in **Power BI** and **Excel** to track inventory and supplier performance for a fashion startup.
- Key Metrics Analyzed:
  - **Total Inventory Value**: ₹577.60k.
  - **On-Time Delivery Rate**: 64%.
  - **Supply Chain Costs**: ₹52.92k.
- Insights:
  - Improved inventory management to avoid stockouts/overstocking.
  - Identified Carrier A as the most reliable with 64% on-time deliveries.
  - Optimized cost distribution for transportation (50.5%) and inventory holding (20.5%).

---

## Next Steps
1. Expand the analysis to include additional datasets and ML models.
2. Explore real-time prediction pipelines for ride-sharing optimization.
3. Apply the methodology to other domains like logistics and retail.

---

This README consolidates your analysis and highlights project strengths. Let me know if you'd like further modifications!
