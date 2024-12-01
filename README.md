# Climate Change Analysis

This project analyzes the relationship between temperature changes and CO₂ concentrations over time, using historical climate data. It includes data preprocessing, statistical analysis, trend visualization, and machine learning for climate pattern clustering and prediction of temperature change based on CO₂ concentration changes.

## Project Overview

The project explores climate change data to understand the trends and correlations between global temperature changes and CO₂ emissions. Key components of the project include:

- **Data Loading and Preprocessing**: Import and clean data from CSV files containing historical temperature and CO₂ concentration records.
- **Statistical Analysis**: Calculate mean, median, and variance of temperature and CO₂ levels.
- **Visualization**: Plot time-series graphs, a correlation heatmap, and scatter plots to understand the relationship between temperature changes and CO₂ levels.
- **Machine Learning**: Apply K-Means clustering to identify similar climate patterns, and use linear regression to predict temperature changes based on CO₂ levels.

## Project Structure

- `temperature.csv`: Contains temperature data for various countries across multiple years.
- `carbon_emission.csv`: Contains CO₂ concentration data recorded monthly, with a focus on global trends.
- `analysis.py`: Contains code for data preprocessing, statistical analysis, and machine learning.
- `visualizations.py`: Contains code for generating visualizations, such as time-series plots, heatmaps, and scatter plots.

## Requirements

To run this project, you need Python 3.x and the following Python packages:

- `pandas`
- `numpy`
- `scipy`
- `plotly`
- `scikit-learn`
