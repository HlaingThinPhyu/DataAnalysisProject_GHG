# Ontario Greenhouse gas emissions analysis
## Introduction
This project investigates the greenhouse gas emissions in Ontario from 2010 to 2021, using a publicly available dataset that records facility-level emissions reported under provincial requirements. 

## Dataset
The dataset includes detailed emissions data categorized by gas types—such as carbon dioxide (CO₂), methane (CH₄), and nitrous oxide (N₂O)—as well as information on reporting and verification bodies, industries, geographic locations, and facility owners. The dataset spans from 2010 to 2021 and includes detailed information on total emissions, gas-specific emissions (such as CO₂, CH₄, N₂O, SF₆, HFCs, PFCs, NF₃), verification details, facility locations, and industrial classification codes (NAICS). Facilities that emit 10,000 tonnes or more of CO₂ equivalent (CO₂e) per year are required to report their emissions, and those emitting 25,000 tonnes or more must have their reports verified by accredited third-party organizations. 

## Objective

Through data cleaning, visualization, and quantitative analysis using Python, we aim to identify emission trends, major polluters, and sector-specific impacts. This helps to better understand the social and economic implications of GHG emissions, and informs policies that balance environmental sustainability with industrial and economic development.



## Tools and Technology Used
Python
pandas: Handling, loading and processing the dataset. 

numpy: Working with numerical data. 

matplotlib \& seaborn: Data visualization. 

scikit learn: Machine learning models: Linear Regression, Decision Tree, Random Forest for forecasting 

## Methodology

1\. **Data Preprocessing**

Source: Ontario GHG Reporting dataset (2010–2021) 

● Filtered data by year, facility owner, and relevant emissions columns. 

● Aggregated total emissions by year and by facility for trend analysis. 

● Filled missing or zero values where appropriate. 

2\. **Exploratory Data Analysis**

● Basic data info and descriptive statistics were printed to understand the structure. 

● Number of unique years and their range were calculated. 

● Yearly total CO2e emissions were aggregated and visualized. 

● Trends of individual gases (e.g., CO₂, CH₄, N₂O) across the years were analyzed. 

3\. **Data Visualization**

● Line plots and bar charts were used to show GHG emission trends. 

● Seaborn and Matplotlib were utilized for informative visuals. 

4\. **Machine Learning Models**

To project greenhouse gas (GHG) emissions from 2022 to 2027, we employed three machine learning regression models: 

Linear Regression: Assumes emissions change at a constant rate over time.

Decision Tree Regressor: Captures non-linear patterns using recursive binary splits. 

Random Forest Regressor: An ensemble method using multiple decision trees to improve prediction robustness. 

Each model was trained on historical yearly data (2010–2021), and predictions were made for future years using the trained models. 



##References##

● https://data.ontario.ca/dataset/greenhouse-gas-emissions-reporting-by-facility 

● https://www23.statcan.gc.ca/imdb/p3VD.pl?Function=getVD\&TVD=1369825 

