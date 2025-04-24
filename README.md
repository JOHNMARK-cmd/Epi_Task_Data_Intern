# Epi_Task_Data_Intern
# EPIDEMIOLOGY TRACK TASK
As an initial task at the Center for Epidemiological Modeling and Analysis, you are presented with a dataset from an epidemiological research project, "Analyzing Regional Trends in Influenza-Like Illness (ILI) in Kenya: A Quantitative Epidemiology Case Study." The study collected data on year (2023-2024), the epidemiological week (epi_week), county, age categories (age_group), percentage of outpatient visits due to ILI (ili_percentage), and the estimated population for that age group in that county (population). 
The objective is to evaluate temporal and county-specific ILI trends and interpret the findings to inform public health decisions.


## a) Descriptive Analysis

### i. Compute a table showing the mean ILI percentage per county per year

To begin this analysis, I will first load the dataset and use the Pandas groupby function to group the data by year and county, then compute the mean ILI percentage.

.