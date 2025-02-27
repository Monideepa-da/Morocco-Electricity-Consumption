Business Problem:
Morocco’s National Power Co is assessing plans for upgrading its infrastructure. As an Analyst I have been asked to analyze seasonality in electricity consumption, to help identify peak load periods across hours of the day and days of the week to help make investments to prevent outages during these time
Key Findings:
January 18 recorded the highest electricity consumption.
Electricity consumption spikes in the evening, drops during the early morning hours, and then rises again.
Power consumption in Zone 1 is higher than in the other two zones
Peak hour with respect to hour of the day are between 6pm to 9pm
Objective 1:
Prepare the data for analysis
To read in relevant columns from the dataset and create a new calculated column for analysis
Objective 2:
Visualize consumption over time
To build a stacked area chart visualizing the power consumption for the month of January 2017.
Objective 3:
Visualize consumption seasonality
To build a heatmap for the average power consumption by day of week & hour of day and report any interesting findings
Learning:
Understood the KPIs(day of week and hours of the day) in the Electricity Company.
 Seaborn also help to get precise value using sns.despine()
Mapping to Day of week always occur alphabetically so need to get the correct sequence we have to use pd.categorical
