# GDP Analysis and Growth Comparison_1960_To_2016

This repository contains an analysis of global GDP data, with a focus on tracking GDP growth across various countries over time. We analyze the dataset, visualize GDP trends, and compare GDP growth rates across selected countries to understand regional economic development patterns.

## Dataset

The dataset used in this analysis is available as `gdp.csv`. This CSV file contains historical GDP data for multiple countries and regions, including columns like:
- `Country Name`: The name of the country or region.
- `Country Code`: The ISO country code.
- `Year`: The year of the recorded data.
- `Value`: The GDP value in US dollars for that year.

You can download the dataset here: [gdp.csv](./gdp.csv)

## Analysis Overview

The analysis is divided into several parts, each exploring different aspects of the GDP data:

### 1. **Dataset Exploration**
   - Initial exploration of data structure, column descriptions, and handling missing values.
   - Generating summary statistics for GDP values by country and year.
   
### 2. **GDP Growth Calculation**
   - Calculated GDP growth percentage year-over-year for each country.
   - Created a new column `GDP_Percent` representing the annual growth rate, making it easier to analyze trends over time.

### 3. **Visualizing GDP Trends**
   - Plotted GDP trends for specific countries using line graphs to observe changes over time.
   - Created comparison charts, such as India vs. the world GDP, for a clearer understanding of relative economic growth.

### 4. **Comparing GDP Growth Across Countries**
   - Used functions to compare GDP growth among selected countries, providing visualizations of GDP percentage growth trends.
   - Visualized GDP data of all countries to see general trends and outliers.

### 5. **Outlier and Missing Data Analysis**
   - Checked for missing data by analyzing GDP data availability for each country between 1960 and 2016.
   - Focused on countries with 57 years of continuous data to avoid inconsistencies due to missing years.

## Code Files

### `gdp_analysis.py`

This script loads `gdp.csv`, calculates GDP growth, and generates plots of GDP values and growth rates for individual countries and groups. It also includes functions for generating bulk GDP plots and comparing GDP growth between countries.

### `gdp_analysis_compare_gdp_growth_comparison.py`

This script focuses on comparing GDP growth between multiple countries and includes additional functions to generate comparative GDP growth plots. It enables detailed side-by-side GDP trend analysis for selected countries.

## Jupyter Notebook

You can also run the analysis in a Jupyter Notebook. Download or open the notebook in Jupyter with the link below:

- [GDP Analysis Notebook (Jupyter)](./GDP_Analysis_01.ipynb)

This notebook provides the full code and analysis in an interactive format, allowing you to make edits and visualize data inline.


## Google Colab Notebooks

You can also run the analysis in Google Colab using the links below:
- [GDP Analysis Notebook](https://colab.research.google.com/github/IshanSrivastav/GDP_Analysis_1960_To_2016/blob/main/GDP_Analysis_01.ipynb)
- [GDP Growth Comparison Notebook](https://colab.research.google.com/github/IshanSrivastav/GDP_Analysis_1960_To_2016/blob/main/GDP_Analysis_02_Compare_GDP_Growth_Comparison.ipynb)

## Requirements

To run the code locally, you need Python 3.x, Jupyter Notebook and the following libraries:
- `pandas`
- `plotly`

Install dependencies with:
```bash
pip install pandas plotly
```

## Running the Analysis
- Clone the repository.
- Place gdp.csv in the same directory as the code files.
- Run gdp_analysis.py to perform the main analysis and generate visualizations.
- Use gdp_analysis_compare_gdp_growth_comparison.py for customized growth comparisons between countries.
- Alternatively, open GDP_Analysis.ipynb in Jupyter Notebook or JupyterLab to interactively run the analysis.

## Sample Results
- The analysis provides insights into GDP growth rates across different countries.
- Observations on outlier countries with unique growth trends.
- Example comparisons: China vs. USA GDP growth, India’s GDP trend relative to the world average.

# Contributing

**Contributions are welcome! If you have ideas for enhancements or spot any issues, feel free to submit a pull request.**
