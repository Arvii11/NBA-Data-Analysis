# NBA Data Analysis

## Overview

This project involves the extraction, cleaning, and analysis of NBA player data to gain insights into player performance across multiple seasons. The analysis focuses on identifying trends, computing player statistics, and exploring correlations between various performance metrics.

## Problem Statement

Analyze NBA player data to identify performance trends, calculate key player statistics, and explore correlations between different metrics. The goal is to enhance decision-making processes in basketball analytics by providing actionable insights based on historical data.

## Solution

- **Data Extraction:** Web scraping was performed using the NBA Stats API to collect detailed player performance data. The data was then consolidated and cleaned for analysis.
- **Data Analysis:** Using Python, the data was analyzed to compute various statistics, identify trends, and explore correlations between different player metrics.
- **Visualization:** Key insights were visualized through various plots and charts to make the data more accessible and understandable.

## Impact

The analysis provides a comprehensive view of player performance, helping teams, analysts, and enthusiasts to make informed decisions. By leveraging this data, stakeholders can better understand player strengths, weaknesses, and overall contributions to their teams.

## Tools Used

- **Python:**
  - `BeautifulSoup`: For web scraping.
  - `Pandas`: For data manipulation and cleaning.
  - `NumPy`: For numerical operations.
  - `Matplotlib` & `Seaborn`: For data visualization.
  - `Jupyter Notebook`: For organizing and executing code.
- **Data Source:** NBA Stats API for real-time player data.
- **Excel:** For storing and managing large datasets.

## Data Extraction and Cleaning

- **Web Scraping:** Data was extracted from the NBA Stats API using Python's `requests` and `BeautifulSoup` libraries.
- **Data Cleaning:** After extraction, the data was cleaned to remove duplicates, handle missing values, and standardize formats for easier analysis.

## Exploratory Data Analysis (EDA)

- **Univariate Analysis:** Key metrics such as player points, assists, rebounds, etc., were analyzed individually to understand their distributions.
- **Bivariate Analysis:** Correlations between different metrics were explored, such as the relationship between points scored and assists.
- **Time-Series Analysis:** Performance trends over multiple seasons were analyzed to identify patterns and anomalies.

## Visualizations

- **Histograms:** To show the distribution of player performance metrics.
- **Scatter Plots:** To explore relationships between two or more variables.
- **Line Charts:** To track performance trends over time.
- **Box Plots:** To identify outliers and understand data spread.

## Key Insights

- **Top Performers:** Identified the top-performing players based on various metrics.
- **Performance Trends:** Discovered trends in player performance over different seasons.
- **Correlation Analysis:** Found significant correlations between certain performance metrics, providing insights into player roles and team dynamics.

## Usage

1. **Clone the Repository:** Download the project files to your local machine.
2. **Install Dependencies:** Install the necessary Python packages.
   ```bash
   pip install
   ```
3. **Run the Notebooks:** Execute the Jupyter notebooks to perform data extraction, cleaning, and analysis.
4. **Explore the Data:** Use the visualizations and insights generated to understand player performance.

## Conclusion

This project demonstrates the power of data analysis in understanding NBA player performance. By extracting and analyzing player data, valuable insights can be gained, aiding teams and analysts in making data-driven decisions.

## Contact

For any questions or feedback, please contact me at arvinthrajmuthu@gmail.com.
