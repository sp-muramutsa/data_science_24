# Netflix Data Analysis

## Overview

In this project, I analyze Netflix data collected from my family's account. The goal is to clean the data and visualize various aspects of our viewing habits using Python's Pandas and Matplotlib libraries. This project is part of my ongoing learning journey in Data Science and serves as a "real world" application of my skills.

## Project Structure

- **Data**
  - `SearchHistory.csv`: Raw data file containing Netflix search history with columns such as `Profile Name`, `Start Time`, `Duration`, `Attributes`, `Title`, `Supplemental Video Type`, `Device Type`, `Bookmark`, `Latest Bookmark`, and `Country`.
  - `ViewingActivity.csv`: Raw data file containing additional viewing activity data.

- **Analysis**
  - **Profile Distribution**: Pie chart visualizing the distribution of viewing time across different profiles.
  - **Total Watch Time**: Bar chart showing the total watch time per profile.
  - **Average Binge Length**: Bar chart depicting the average length of binge-watching sessions per profile.
  - **Device Usage**: Bar chart displaying the distribution of device types used for watching content.
  - **Country Distribution**: Bar chart illustrating the distribution of viewing by country.
  - **Title Word Cloud**: Word cloud visualization of frequently watched titles.
  - **Weekly Profile Occurrences**: Line chart showing profile activity over weeks.
  - **Displayed Name Word Cloud**: Word cloud for the names of displayed content.

## Steps

1. **Load Data**

   Load the data from `SearchHistory.csv` and `ViewingActivity.csv`, and explore their structure.

2. **Profile Distribution**

   Create a pie chart to visualize how viewing time is distributed among different profiles.

3. **Total Watch Time**

   Aggregate total watch time per profile and plot it as a bar chart.

4. **Average Binge Length**

   Calculate the average binge length per profile and visualize it using a bar chart.

5. **Device Usage**

   Analyze the distribution of device types used and plot a bar chart.

6. **Country Distribution**

   Visualize the distribution of viewing by country using a bar chart.

7. **Title Word Cloud**

   Generate a word cloud from the titles of watched content, excluding common stopwords.

8. **Weekly Profile Occurrences**

   Analyze profile activity over weeks and plot it on a line chart.

9. **Displayed Name Word Cloud**

   Create a word cloud for displayed content names.

## Visualization Examples

The analysis and visualizations are detailed in `netflix.ipynb`. 

## Contributing

Feel free to open issues or submit pull requests if you have suggestions or improvements!

## Acknowledgments

Thanks to Python Data Science December for inspiring the project.
