# Automobile Sales Statistics Dashboard

This is a simple interactive dashboard built with **Dash**, **Plotly**, and **Pandas**. It helps you explore automobile sales data in the United States.

## Features

- Select between two report types:
    - **Yearly Statistics** – view sales data for a selected year
    - **Recession Period Statistics** – view sales data during recession periods
- Interactive visualizations:
    - Line chart: Average automobile sales by year
    - Line chart: Average automobile sales by month
    - Bar chart: Average vehicles sold by type
    - Pie chart: Advertising expenditure by vehicle type
    - Bar chart: Effect of unemployment rate on vehicle sales during recession

## How to Run

1. Install the required libraries:
    ```bash
    pip install dash pandas plotly
    ```

2. Run the app:
    ```bash
    python app.py
    ```

3. Open your browser and navigate to:
    ```
    http://127.0.0.1:8050/
    ```

## Dataset

The dashboard uses the following dataset:

[Automobile Sales Dataset (CSV)](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv)

The data is loaded automatically when the app starts.

## Author

Created by Jakub as part of a data visualization project.

