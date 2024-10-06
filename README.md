# Road Crash Data Analysis
Case study on road crashes for South Australia, conducted in Python and including Tableau storyboard

## Project Overview
The case study was part of the assignments for the Career Foundry Data Analytics course. The task was to come up with a project idea, select dataset, and build a dashboard in Tableau that would showcase the well-curated results of an advanced exploratory analysis conducted in Python. 

## Data Overview
The data for the project had to conform to the following rules:

- be open source
- come from an authentic/authoritative source
- include non-anonymized column names
- be no more than 3 years old
- contain at least 2 continuous variables
- contain at least 2 categorical variables
- contain at least 1,500 rows
- include a geographical component with at least 2 different values

With these restrictions in mind, I sourced [Road Crash Data in South Australia, 2019 to 2023](https://data.sa.gov.au/data/dataset/21386a53-56a1-4edf-bd0b-61ed15f10acf/resource/78d24425-6c14-426e-8895-d414c2a12521/download/2019-2023_data_sa_as_at_20240821.zip) from the South Australian Government’s Department for Infrastructure and Transport.

The shapefile on [South Australia's suburb boundaries](https://data.gov.au/dataset/ds-dga-bcfcfc9a-7c8d-479a-9bdf-b95ca66ad29a/details) is sourced from the Australian Government Data Website.

## Analysis Criteria
- Exploratory analysis through visualizations (scatterplots, correlation heatmaps, pair plots, and categorical plots)
- Geospatial analysis using a shapefile
- Regression analysis
- Cluster analysis
- Time-series analysis
- Analysis narrative and final results (presented in the dashboard)

## Business Questions
- What are the most common types of crashes? Are there any trends in crash types over time?
- What are the most dangerous times of day, days of the week, or weather conditions for crashes?
- How do crash rates vary by location?
- Is there a correlation between the severity of a crash and factors like vehicle type, driver age, or alcohol/drug involvement?
- Does seat belt and helmet usage impact the severity of injuries sustained in crashes?
- How can the data be used to identify high-risk areas or demographics for targeted safety interventions?

## Tools and Technologies
- Anaconda-Navigator: A graphical user interface that simplifies the installation and management of Python distributions, packages, and environments.
- Jupyter Notebook: A popular environment for interactive data science.
- Python: The primary programming language used for data analysis and visualisation.
- pandas: A powerful library for data manipulation and analysis.
- NumPy: A library for numerical computations.
- matplotlib.pyplot: A plotting library for creating static, animated, and interactive visualisations.
- seaborn: A high-level data visualisation library built on Matplotlib.
- folium: A Python library for creating interactive maps. It's particularly useful for visualizing geographical data.
- json: A standard format for storing and exchanging data.
- scikit-learn (sklearn): A machine learning library that provides algorithms for classification, regression, clustering, and other tasks.
- pylab: A module that combines the functionality of NumPy and Matplotlib, making it easier to create plots.
- quandl: A data platform that provides access to financial and economic data.
- statsmodels.api: A Python module that provides statistical modeling tools, including regression analysis, time series analysis, and hypothesis testing.
- Tableau Public: A cloud-based platform for creating interactive visualizations and dashboards.

## Tableau Storyboard
Link to [Tableau Storyboard](https://public.tableau.com/shared/C37XQJ9T8?:display_count=n&:origin=viz_share_link) looking at the relationship between speed limit and number of casualties per crash.
