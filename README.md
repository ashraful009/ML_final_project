# Sales Data Analysis Project

This project analyzes sales data from an Excel file (`sell.xlsx`) using Python. The analysis includes data cleaning, feature extraction, and visualization to provide insights into sales trends, top-selling products, and customer behavior.

## Objective

The objective of this project is to process and analyze raw sales data to uncover meaningful insights that can help businesses make data-driven decisions. By cleaning the data, extracting key features, and visualizing trends, this project aims to provide actionable insights into customer preferences and sales performance.

## Goal

The goal of this project is to:
- Identify top-selling products (sizes and colors).
- Understand sales trends over time (monthly trends).
- Highlight key areas for delivery and customer concentration.
- Provide a summary of metrics to assist in strategic planning and decision-making.

## Features

1. **Data Cleaning**:
   - Dropped unnecessary columns.
   - Converted date columns to proper datetime format.
   - Removed duplicates.

2. **Feature Extraction**:
   - Extracted `Size` and `Color` from the `Note` column.
   - Extracted `Area` from the `Recipient Address` column.

3. **Visualizations**:
   - Top-selling sizes and colors.
   - Monthly sales trends.
   - Payment status distribution.
   - Top delivery areas.

4. **Summary Metrics**:
   - Identified the top area, top-selling size, and top-selling month.
   - Calculated total sales for each month.

## Libraries Used

- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `matplotlib` and `seaborn` for data visualization.
- `re` for regular expression-based feature extraction.

## How to Run

1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

2. Place the `sell.xlsx` file in the project directory.

3. Run the Jupyter Notebook or Python script to execute the analysis.

## Results

- **Top-Selling Sizes and Colors**: Visualized the most popular product attributes.
- **Monthly Sales Trends**: Identified seasonal patterns in sales.
- **Payment Status**: Analyzed the distribution of paid vs unpaid orders.
- **Top Delivery Areas**: Highlighted areas with the highest number of orders.

## Future Enhancements

- Automate the analysis pipeline for real-time data updates.
- Integrate machine learning models to predict future sales trends.
- Add more advanced visualizations for deeper insights.# Sales Data Analysis Project

This project analyzes sales data from an Excel file (`sell.xlsx`) using Python. The analysis includes data cleaning, feature extraction, and visualization to provide insights into sales trends, top-selling products, and customer behavior.

## Features

1. **Data Cleaning**:
   - Dropped unnecessary columns.
   - Converted date columns to proper datetime format.
   - Removed duplicates.

2. **Feature Extraction**:
   - Extracted `Size` and `Color` from the `Note` column.
   - Extracted `Area` from the `Recipient Address` column.

3. **Visualizations**:
   - Top-selling sizes and colors.
   - Monthly sales trends.
   - Payment status distribution.
   - Top delivery areas.

4. **Summary Metrics**:
   - Identified the top area, top-selling size, and top-selling month.
   - Calculated total sales for each month.

## Libraries Used

- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `matplotlib` and `seaborn` for data visualization.
- `re` for regular expression-based feature extraction.

## How to Run

1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn