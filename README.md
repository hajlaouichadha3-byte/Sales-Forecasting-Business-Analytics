# Sales Forecasting & Business Analytics

## Project Overview
This project analyzes online retail transactions to identify sales trends, explore product and country performance, and forecast daily sales using Machine Learning.

## Objectives
- Analyze and clean retail transaction data.
- Calculate sales revenue and identify top-performing products.
- Compare sales performance across countries.
- Visualize monthly and daily sales trends.
- Build a Random Forest model to forecast daily sales.
- Evaluate predictions using MAE and RMSE.

## Dataset
The project uses the **Online Retail** dataset from the UCI Machine Learning Repository.

Source: https://archive.ics.uci.edu/dataset/352/online+retail

## Technologies
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Machine Learning
A Random Forest Regressor is trained using historical sales features:
- Previous day's sales
- Sales from seven days earlier
- Rolling average of the previous seven days

The data is split chronologically into training and testing sets to evaluate the model on later dates.

## Evaluation Metrics
- **MAE:** Mean Absolute Error
- **RMSE:** Root Mean Squared Error

The results depend on the dataset and model configuration. The model should be compared with a simple baseline before being considered reliable.

## Project Files
- `Sales_Forecasting_Analysis.ipynb`: Data analysis, visualizations, and model training.
- `sales_forecast_results.csv`: Actual and predicted sales on the test period.
- `sales_forecasting_summary.csv`: Summary of evaluation metrics.
- `Online Retail.xlsx`: Original dataset.

## Future Improvements
- Compare Random Forest with baseline and other forecasting models.
- Add calendar features such as day of week and month.
- Build an interactive dashboard using Streamlit.
- Improve evaluation and forecasting performance.

## Author
Data Science Student
