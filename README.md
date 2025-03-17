# Pandas & NumPy - Gun Data Exploration

## Project Overview
In this project, I conducted an open-ended data analysis using the FBI’s National Instant Criminal Background Check System (NICS) data and state-level U.S. census data. The goal was to explore patterns and correlations in firearm background checks across different states and time periods. Using Pandas and NumPy, I analyzed the data to answer questions about potential factors influencing gun background checks, including political and demographic variables. The findings are tentative and exploratory, as the project focuses on descriptive analysis rather than inferential statistics or machine learning.

## Dataset Information
The dataset includes:
- **NICS Data**: Contains monthly firearm background check numbers by state and firearm type. This data comes from the FBI's NICS, which is used by gun shops to verify customer eligibility for purchasing firearms or explosives.
- **U.S. Census Data**: Provides state-level demographic information from census.gov. While most variables have a single data point per state (from 2016), some variables span multiple years.

This project explores general patterns in the data, such as potential relationships between state demographics and the number of background checks, as well as whether the political party of the sitting President has any effect on the volume of checks. 

## Project Files
- **Data Files**:
  - `US_Census_Data.csv` - Contains U.S. Census data on state demographics.
  - `gun_data.csv` - Contains firearm background check data from the NICS.

- **Jupyter Notebook**:
  - `Investigate_a_Dataset.ipynb` - The Jupyter Notebook containing the full analysis. It can be viewed directly on GitHub or downloaded and run locally in a Jupyter environment.
  
- **HTML Version**:
  - `Investigate_a_Dataset.html` - An HTML version of the Jupyter Notebook, viewable in any browser if downloaded.

Both the notebook and the HTML file contain the data analysis, findings, and visualizations related to the questions explored.