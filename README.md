`Sales & Demand Forecasting using the Superstore Dataset

Future Interns – Machine Learning Task 1 

Project Overview

This project focuses on predicting future sales using historical retail data from the Superstore Sales Dataset. Sales forecasting is an important business application of Machine Learning because it helps organizations make better decisions related to inventory management, staffing, budgeting, and overall business planning.

The goal of this project was to analyze past sales trends, build forecasting models, and generate future sales predictions that can support data-driven business decisions.

Files Included

| File                                 | Description                                                                                            |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `sales_forecasting.ipynb`            | Complete notebook containing data preprocessing, analysis, model building, evaluation, and forecasting |
| `superstore.csv`                     | Dataset used for the project                                                                           |
| `README.md`                          | Project documentation                                                                                  |

Dataset

This project uses the Superstore Sales Dataset, which contains retail transaction records including order dates, product categories, regions, and sales values.

Dataset Source:
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

Project Workflow

1. Data Cleaning

* Loaded and inspected the dataset
* Handled date formatting issues
* Checked for missing values and duplicates
* Prepared the data for analysis

2. Feature Engineering

Created time-based features such as:

* Year
* Month
* Quarter
* Seasonal indicators
* Lag features
* Rolling averages

These features help the model learn sales patterns over time.

3. Exploratory Data Analysis

Analyzed:

* Overall sales trends
* Monthly and seasonal patterns
* Regional performance
* Product category sales

4. Model Building

Multiple forecasting approaches were tested:

* Seasonal Naive Baseline
* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

5. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)

The Linear Regression model achieved the most balanced performance and was selected for forecasting future sales.

Results

| Model             | MAE   | RMSE   | MAPE  |
| ----------------- | ----- | ------ | ----- |
| Seasonal Naive    | 8,552 | 11,700 | 62.9% |
| Linear Regression | 7,766 | 9,225  | 49.4% |
| Random Forest     | 8,259 | 9,829  | 49.1% |
| Gradient Boosting | 7,956 | 9,599  | 47.9% |

Forecast

The model predicts approximately **$124,000 in total sales over the next 12 weeks** based on historical sales patterns.

Business Insights

The generated forecasts can help businesses:

* Plan inventory levels more effectively
* Reduce stock shortages and overstock situations
* Improve budgeting and cash-flow planning
* Support workforce and staffing decisions
* Identify seasonal demand trends

By using historical sales data and Machine Learning techniques, businesses can make more informed decisions and improve operational efficiency

Limitations

* The dataset contains only four years of historical data.
* Holiday season behavior may vary from year to year.
* Forecasts should be updated regularly as new sales data becomes available.

Conclusion

This project demonstrates how Machine Learning can be applied to real-world business problems. By forecasting future sales, organizations can better prepare for demand fluctuations and make smarter operational decisions.

Author - by Devaki
