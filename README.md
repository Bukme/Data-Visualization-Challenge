# Pymaceuticals Inc.

---

### Overview

This project is an analysis of the data from Pymaceuticals Inc., which specializes in anti-cancer pharmaceuticals. The analysis involves a study of the effectiveness of various drug regimens on tumor growth in mice.

### Dependencies and Setup

The project is developed using Python and requires the following libraries:

- `matplotlib` for plotting
- `pandas` for data manipulation
- `scipy.stats` for statistical analysis

### Data

The data consists of two CSV files:

- `Mouse_metadata.csv`: Contains information about each mouse, including its ID, weight, age, and sex.
- `Study_results.csv`: Contains the results of the drug regimen study, including each mouse's ID, timepoint, tumor volume, and metastatic sites.

### Analysis Steps

1. **Data Preparation**:
   - Import the necessary libraries and dependencies.
   - Read the CSV files into Pandas DataFrames.
   - Merge the two DataFrames into a single DataFrame.
   - Clean the data by removing duplicate entries and ensuring data integrity.

2. **Summary Statistics**:
   - Calculate summary statistics (mean, median, variance, standard deviation, and SEM) of tumor volume for each drug regimen.
   - Visualize the summary statistics using Pandas and Matplotlib.

3. **Bar and Pie Charts**:
   - Generate bar plots to show the distribution of observations for each drug regimen.
   - Create pie charts to illustrate the distribution of male and female mice in the study.

4. **Quartiles, Outliers, and Boxplots**:
   - Determine the final tumor volume for mice treated with specific drug regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).
   - Calculate quartiles and identify potential outliers.
   - Visualize the distribution of tumor volume using boxplots.

5. **Line and Scatter Plots**:
   - Plot tumor volume vs. timepoint for a single mouse treated with Capomulin.
   - Plot mouse weight vs. average tumor volume for the Capomulin regimen.
   
6. **Correlation and Regression**:
   - Calculate the correlation coefficient between mouse weight and average tumor volume.
   - Perform linear regression analysis to model the relationship between mouse weight and tumor volume.
   - Visualize the regression line on a scatter plot.

### Analysis Report

After careful analysis of the data, the following conclusions can be drawn:

- There is a strong positive linear relationship between mouse weight and average tumor volume, with a correlation coefficient of 0.84.
- As mouse weight increases, the average tumor volume tends to increase as well, indicating a tendency for heavier mice to have larger average tumor volumes.

This analysis suggests that there is a strong association between mouse weight and tumor volume, highlighting the importance of considering weight factors in anti-cancer drug studies.

### Author

**Bukola Fatile**


## References

- Pandas. (n.d.). *Data wrangling tidy data - pandas*. [https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)

- Matplotlib. (n.d.). *Matplotlib 3.8.1 documentation*. [https://matplotlib.org/stable/](https://matplotlib.org/stable/)

- Pandas. (n.d.). *pandas.DataFrame.set_index - pandas 2.1.2 documentation*. [https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.set_index.html](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.set_index.html)

- Willems, K. (2021, May 17). *Pandas cheat sheet for data science in Python*. DataCamp. [https://www.datacamp.com/cheat-sheet/pandas-cheat-sheet-for-data-science-in-python](https://www.datacamp.com/cheat-sheet/pandas-cheat-sheet-for-data-science-in-python)

- YouTube. (2020, August 16). *Correlation and linear regression in python* [Video]. YouTube. [https://www.youtube.com/watch?v=e-dTBeBe1b8](https://www.youtube.com/watch?v=e-dTBeBe1b8)

- Various class materials, discussions, and online resources.

