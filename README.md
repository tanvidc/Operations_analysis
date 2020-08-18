# LifeSoda Data Analysis and modeling flavor popularity

This weekend project explores data from 50 vending stations of LifeSoda, a social enterprise that sells clean water and mineral and vitamin enriched seltzer at a subsidized cost to prevent malnutrition in some communities in developing countries.
Flavors, water tanks (500, 750, 1000L), and CO2 are consumable components. Solar powered battery lasts for 24 hours after power loss. Telemetry data might be transmitted periodically.
Each person can vend once every 8 hours, and drink is 0.5 or 1L. May mix flavors up to the amount prepaid.

## Goal
Start by understanding the data, create summary statistics, visualizations, and tabulations to gain data format and operations insights, and to enlist follow up questions.
Then, quantify flavor popularity and recommend new flavors, or a plan for field testing flavor recommendations.

## Data
LifeSoda's lead dev sent us a data dump. Each station data is a station_DDD.csv file, and metadata file indicates the countries corresponding to the stations. The data is clean and structured, but this is all the detail we have in the beginning. We describe the data more as we examine it in LifeSoda_analysis.ipynb.

## Results
Results and insights are well described in the notebooks. Some glimpses:
Consumption drops because of downtime of water tank. Operations can be improved by recommending to place orders given delivery time and demand projection.
![Water_consumption](https://github.com/tanvidc/2020_DrivenData_TanviChheda/blob/master/data/water_consumption_plot.PNG)
Ratings based on time taken to consume flavors shows very differing tastes,
![Ratings](https://github.com/tanvidc/2020_DrivenData_TanviChheda/blob/master/data/ratings_table.PNG)
