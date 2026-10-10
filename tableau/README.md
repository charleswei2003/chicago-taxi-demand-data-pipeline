# Tableau Dashboard

| | |
| --- | --- |
| **Workbook** | MSBA405 Final Project Dashboard |
| **Live link** | [Open on Tableau Public](https://public.tableau.com/views/MSBA405FinalProjectDashboard/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) |
| **Data** | The 23-column tract-month table that `pipeline.sh` loads into Snowflake |

## What the dashboard shows

The dashboard analyzes monthly 2017 Chicago taxi pickup demand at the
census-tract level alongside ACS demographic, commuting, education, income, and
vehicle-availability characteristics.

| View | Question it answers |
| --- | --- |
| Trips per capita heatmap | Where does taxi demand concentrate once population is taken into account? |
| No-car map | Which tracts have the most households without a vehicle? |
| Walk share vs. trips per capita | Do neighborhoods where people walk to work use taxis more? |
| Car share vs. trips per capita | How does commuting by car relate to taxi use? |
| No-car share vs. trips per household | Do car-free households lean on taxis? |
| Median income vs. log trips per capita | How does taxi demand scale with neighborhood income? |
