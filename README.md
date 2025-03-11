# Transportation and Economic Indicators Analysis
This project explores the relationship between transportation spending and various economic indicators across US states.  Using publicly available datasets, the analysis investigates correlations and potential causal relationships.

## Features
* Data ingestion and preprocessing from multiple CSV and Excel files.
* Data cleaning and handling of missing values.
* Exploratory data analysis using visualizations.
* Statistical modeling using ordinary least squares (OLS) regression.
* Model evaluation using R-squared and RMSE.
* Time series analysis of real GDP over time.

## Usage
This project is implemented using Jupyter Notebooks. Each notebook performs a specific task related to data processing, analysis, and visualization.  The notebooks are self-contained and can be run independently in a Jupyter environment.

## Installation
1. **Install Python:** Ensure you have Python 3.7 or higher installed.
2. **Create a virtual environment (recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Linux/macOS
   venv\Scripts\activate  # On Windows
   ```
3. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```
   (Note: A `requirements.txt` file should be created listing all project dependencies – see Dependencies section below)

## Technologies Used
* **Python:** The primary programming language for data manipulation, analysis, and modeling.
* **Pandas:** Used for data manipulation and analysis.
* **NumPy:** Used for numerical operations and array handling.
* **Matplotlib & Seaborn:** Used for data visualization and creating plots.
* **Statsmodels:** Used for statistical modeling, particularly OLS regression.
* **Scikit-learn:** Used for machine learning algorithms (although only Linear Regression is used here).
* **Openpyxl:** Used to read and process Excel files.

## Statistical Analysis
The analysis employs several statistical methods:

* **Data Cleaning:** Handling missing values and data inconsistencies.
* **Exploratory Data Analysis (EDA):** Visualizing data distributions and relationships using scatter plots.
* **Ordinary Least Squares (OLS) Regression:** Modeling the relationships between transportation spending percentages (Highways, Airports, Transit) and economic indicators (Real GDP per capita, Gini index, Poverty rate, Unemployment rate).
* **R-squared and RMSE:** Evaluating the goodness of fit and prediction accuracy of the regression models.
* **Time Series Analysis:** Examining the changes in real GDP per capita over time.

*README.md was made with [Etchr](https://etchr.dev)*