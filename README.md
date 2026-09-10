

# Task 2: Unemployment Analysis with Python

## Objective

The objective of this project is to perform Exploratory Data Analysis (EDA)
on unemployment data in India to identify regional and temporal trends and
analyze the impact of the COVID-19 pandemic on unemployment rates.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## Dataset

The project uses the **Unemployment in India** dataset.

The dataset contains unemployment and labour market information for
different regions of India over multiple time periods.

The main variables include:

- Region
- Date
- Frequency
- Estimated Unemployment Rate
- Estimated Employed
- Estimated Labour Participation Rate

## Project Workflow

1. Load the unemployment dataset
2. Create a Pandas DataFrame
3. Inspect the dataset shape and structure
4. Check data types
5. Check for missing values
6. Clean column names
7. Convert the Date column to datetime format
8. Generate descriptive statistics
9. Calculate region-wise average unemployment rates
10. Analyze month-wise unemployment trends
11. Compare unemployment rates for at least three regions
12. Identify the top 10 regions with the highest average unemployment rate
13. Analyze correlations between unemployment, employment and labour participation
14. Create a correlation heatmap
15. Split the data into pre-COVID and post-COVID periods
16. Calculate mean unemployment rates for both periods
17. Compare pre-COVID and post-COVID unemployment rates
18. Analyze the impact of COVID-19 on unemployment
19. Draw conclusions from the analysis

## Data Cleaning

The dataset was cleaned before performing the analysis.

The cleaning process included:

- Removing unnecessary spaces from column names
- Checking for missing values
- Handling missing observations where necessary
- Converting the Date column into datetime format
- Sorting the data chronologically

## Exploratory Data Analysis

EDA was performed to understand regional and temporal patterns in
unemployment.

The analysis included:

- Dataset shape
- Data types
- Null value checking
- Descriptive statistics
- Region-wise average unemployment
- Month-wise unemployment trends
- Regional time-series comparison
- Top 10 regions by average unemployment

## Time-Series Analysis

A time-series analysis was performed to observe how unemployment rates
changed over time.

Line charts were created to:

- Show the overall month-wise unemployment trend
- Compare unemployment rates across three selected regions
- Identify major changes in unemployment over time

## Regional Analysis

The average unemployment rate was calculated for each region.

The regions were then compared to identify areas with relatively higher
and lower average unemployment rates.

A bar chart was created to display the **top 10 regions with the highest
average unemployment rate**.

## Correlation Analysis

Correlation analysis was performed using the following variables:

- Unemployment Rate
- Estimated Employed
- Labour Participation Rate

A **correlation heatmap** was created using Seaborn to visualize the
strength and direction of relationships between these variables.

Correlation indicates statistical association between variables and does
not necessarily imply causation.

## COVID-19 Analysis

The dataset was divided into two periods:

- **Pre-COVID:** Before March 2020
- **Post-COVID:** March 2020 onwards

The average unemployment rate and labour participation rate were calculated
for both periods.

A comparison chart was created to examine changes in unemployment during
the COVID-19 period.

## Visualizations

The project includes:

- Month-wise unemployment rate line chart
- Three-region unemployment time-series line chart
- Top 10 regions unemployment bar chart
- Employment indicators correlation heatmap
- Pre-COVID vs post-COVID comparison chart
- COVID-19 unemployment trend visualization

## Key Findings

The analysis shows that unemployment rates vary across different regions
of India.

Unemployment also changes over time, with different regions showing
different patterns and fluctuations.

The top 10 analysis identifies regions with the highest average
unemployment rates.

The correlation analysis shows the statistical relationships between
unemployment, employment and labour participation.

The pre-COVID and post-COVID comparison helps demonstrate the changes in
unemployment associated with the COVID-19 period.

## Conclusion

This project demonstrates how Python can be used to perform Exploratory
Data Analysis on real-world unemployment data.

Using Pandas, Matplotlib and Seaborn, the project analyzes regional
differences, time-based trends, labour-market relationships and the impact
of the COVID-19 pandemic on unemployment in India.

## Project Files

- `Unemployment_Analysis_with_Python.ipynb` - Complete Jupyter/Google Colab notebook
- `Unemployment in India.csv` - Dataset used for the analysis
- `README.md` - Project documentation
