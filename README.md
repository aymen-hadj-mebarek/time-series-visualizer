# FreeCodeCamp - Page View Time Series Visualizer

This project is part of the Data Analysis with Python certification program offered by freeCodeCamp. The goal of this project is to visualize data from the freeCodeCamp forum page views using various plotting techniques, including line plots, bar plots, and box plots. 

This project has helped me enhance my data analysis and visualization skills, providing a deeper understanding of how to effectively represent and interpret data insights.

## Table of Contents
- [FreeCodeCamp - Page View Time Series Visualizer](#freecodecamp---page-view-time-series-visualizer)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Visualizations](#visualizations)
    - [Line Plot](#line-plot)
    - [Bar Plot](#bar-plot)
    - [Box Plots](#box-plots)
  - [Data Cleaning](#data-cleaning)

## Project Overview

The project involves analyzing and visualizing the time series data of daily page views on the freeCodeCamp forum from May 2016 to December 2019. The primary objectives are:

1. **Data Cleaning**: Removing outliers and ensuring the data is in a usable format.
2. **Visualization**: Creating various plots to illustrate trends, seasonality, and distributions within the data.

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
```bash
git clone https://github.com/aymen-hadj-mebarek/time-series-visualizer.git
```
2. Navigate to the project directory:
    
```bash
cd time-series-visualizer
```

3. Install the required Python packages:
    
```bash
pip install -r requirements.txt
```    

## Usage

After setting up the environment, you can open the Jupyter Notebook included in this repository to explore the visualizations:

1. Launch Jupyter Notebook.
    
2. Open the `time_series_visualizer.py.ipynb` notebook file.
    
3. Run the notebook cells to execute the data analysis and generate the visualizations.
    

## Visualizations

### Line Plot

This plot shows the daily page views on the freeCodeCamp forum from May 2016 to December 2019. The line plot provides a clear view of the overall trend in page views over time.

### Bar Plot

The bar plot visualizes the average page views per month, grouped by year. This plot helps in understanding the monthly variations and overall trends across different years.

### Box Plots

The box plots consist of two separate visualizations:

- **Year-wise Box Plot (Trend):** Displays the distribution of page views across different years, helping to identify trends.
- **Month-wise Box Plot (Seasonality):** Shows the distribution of page views across different months, highlighting any seasonal patterns.

## Data Cleaning

The dataset used in this project was cleaned by:

1. Removing the top and bottom 2.5% of page view data to eliminate outliers.
2. Sorting the data by date after cleaning.