# Movie Correlation With Python

## Overview

This project involves analyzing a movies dataset to gain insights into various aspects, including budget, gross earnings, and their correlation. The process encompasses data cleaning, visualization, and deriving meaningful conclusions about factors influencing a movie's success.

## Key Steps

### 1. Importing Packages

Essential Python packages, such as Pandas, NumPy, Seaborn, and Matplotlib, are imported for data analysis and visualization.

### 2. Data Loading

The dataset (`movies.csv`) is loaded into a Pandas DataFrame for analysis.

### 3. Data Cleaning

Missing data is handled, and data types for 'budget' and 'gross' columns are converted to integers.

### 4. Time Feature Extraction

The release year is extracted from the 'released' column, creating a new 'yearcorrect' column.

### 5. Sorting and Duplicates

The data is sorted by gross earnings, and duplicate rows are checked and removed.

### 6. Outlier Detection

Box plots are generated to identify potential outliers in 'gross' and 'budget' columns.

### 7. Correlation Analysis

Scatter plots and heatmaps visualize the correlation between 'budget' and 'gross' and other numeric features.

### 8. Exploratory Data Analysis (EDA)

EDA includes analyzing the correlation between votes and gross earnings.

### 9. Top Companies and Genres

Top companies with the highest earnings and the most profitable movie genres are identified and visualized.

### 10. Conclusion

The analysis concludes by summarizing key findings and insights, offering a holistic view of the movie dataset.

This project provides a deeper understanding of relationships and trends within the dataset, offering valuable insights for movie industry enthusiasts and professionals.
