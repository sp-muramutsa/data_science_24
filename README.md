# Netflix Viewing and Search Data Visualization

## Overview

This project involves analyzing and visualizing Netflix viewing and search history data. The goal is to provide insights into user activity and search patterns through interactive visualizations. The data is processed and displayed using Python and various visualization libraries.

## Features

- **Viewing Activity Analysis**: Visualize viewing activity over time, including total viewing hours and activity patterns. This helps in understanding user engagement and viewing trends.

- **Search History Analysis**: Examine search patterns and frequencies. This feature provides insights into what users are searching for and how search behavior changes over time.

- **Interactive Visualizations**: Use interactive charts to explore and compare different aspects of viewing and search history data. Users can interact with the charts to drill down into specific time periods or categories.

## Project Structure

- **data/**
  - `SearchHistory.csv`: Raw data containing information about search queries made by users.
  - `ViewingActivity.csv`: Raw data containing information about user viewing activity.

- **notebooks/**
  - `netflix.ipynb`: Jupyter notebook that includes:
    - Loading and preprocessing data from `SearchHistory.csv` and `ViewingActivity.csv`.
    - Creating visualizations such as time series plots and bar charts to analyze viewing and search patterns.
    - Generating insights and trends based on the processed data.

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- plotly

## Installation and Setup

1. **Clone the Repository**:
   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/sp-muramutsa/netflix.git
   cd netflix
   ```

3. **Install Dependencies**:
   Install the required Python libraries using pip:

   pip install pandas matplotlib seaborn plotly

4. **Prepare Data**:
   Ensure that `SearchHistory.csv` and `ViewingActivity.csv` are present in the `data/` directory.

5. **Run Analysis**:
   Open the `netflix.ipynb` notebook in Jupyter or any compatible environment and execute the cells to perform data analysis and generate visualizations.

## Example

A sample of the analysis and visualizations can be found in `netflix.ipynb`.
