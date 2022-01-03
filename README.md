# G20 Countries Analysis
Repository for my work on the analysis on the G20 nations.<br>
### Dataset: 
- The data for this analysis was taken from the World Bank website: https://data.worldbank.org/country/
- I selected the countries which are a part of the G20 and downloaded `.csv` files for every country, containing information on various economic and social aspects.
### Data Preprocessing:
- Used **Pandas** to clean the `.csv` files by:
  - dropping useless columns, 
  - tranposing the tables, 
  - renaming certain columns 
  - concatenating all 20 tables for each country,
  - saving the modified file to reuse again.
### Visualizations:
#### Tableau Dashboard:
- View the dashboard here: https://public.tableau.com/views/G20-Dashboard/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
#### Exploratory Data Analysis in Jupyter Notebooks:
- View the Notebook here: https://github.com/AnityaGan9urde/g20-countries-analysis/blob/main/g20_analysis.ipynb
### 💡Insights:
- Fertility Rates are at an all time low for every country, so low that countries like South Korea, Japan and Germany have fertility rates even lower than 1.3, South Korea having the lowest at 0.918. This means that every couple is having one or no child due to various reasons, which is halving the population of that nation year by year and giving rise to more elderly and dependent citizens.
- Life Expectancy is shown to have increased in the recent decades. Countries like India, China are showing rapid increase in their life expectancy due to recent economic booms and improving health infrastructure.
- Both agricultural jobs and rural populations are showing a downward trend. This is mainly because as economies develop the majority of the jobs become service related. Modern agricultural practices have decreased the demand for a huge labour force and rural to urban migration has increased.
- Electricity Consumption has also increased recently due to rapid urbanization and increasing reliance on electrical appliances of all sorts.
