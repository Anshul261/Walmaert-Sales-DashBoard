# Sales Forecasting and Analytics
# Walmaert-Sales-Dashboard

## Features
- Interactive sales data visualizations
- Forecasting of future sales trends
- Analysis of historical sales data

## Overview
The Walmaert-Sales-Dashboard project is a platform that utilizes publicly available Walmart sales data to provide users with insights and forecasts on future sales. The dashboard is designed to offer a comprehensive analysis of sales trends using interactive visualization tools that are easy to understand, even for those without technical knowledge.

Users can access the dashboard to view the company's gross revenue, average monthly sales, and revenue generated during any selected time period. Additionally, the dashboard showcases interesting correlations between sales and various economic factors such as employment rates and fuel prices. By comparing sales generated during different periods, users can gain insights into how these factors impact sales.

Another key feature of the project is the use of sales data to forecast the company's future sales. This information is then presented in the form of a graph for easy visualization of the results.

## Technologies Used
- **Dash**: A web application framework for Python.
- **Plotly**: Graphing library for making interactive, publication-quality graphs in Python.
- **scikit-learn**: A library used to create models
- **numpy**: A library used to assits in using dataframes
- **pandas**: A library used to manipulate and load the data sets
- **Jupyter Notebook**: An open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text.

## How to Run
1. Clone the repository to your local machine.
2. Ensure Python and Jupyter Notebook are installed.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Navigate to the project directory and launch the dashboard by running the cells inthe `main.ipynb` file.

## Dataset Used
The project uses the Walmart sales dataset https://www.kaggle.com/datasets/yasserh/walmart-dataset, which includes various features like weekly sales, holiday flags, and department information. 
This dataset is critical for understanding sales patterns and forecasting future trends.

## Future Work
- Integration with real-time data sources.
- Expansion of forecasting models for greater accuracy.
- Addition of user input capabilities to customize analyses.
