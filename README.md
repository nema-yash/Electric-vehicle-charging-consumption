# Investigating EV charging data


**Introduction:**

Got an opportunity to work with a home energy consumption monitoring technology company through XN project at Northeastern University from Oct 2021 to Dec 2021 whose goal is to help customers understand their household energy consumption, understand their habits, and ultimately reduce their energy footprint and save money.

**Problem Statement**
With the company business goal in mind formulated the following problem statement:- 
**Help equip customers with insights about their EVs energy consumption and help predict future charging behavior.**

**Dataset summary**
1) Dataset provided consisted of 1200 Households across the USA with one or more EVs of various brands for each Household. 
2) For each EV hourly energy consumption was provided. 
3) Columns: House number, State, Zip3, Time, EV0:EV3

Issues: Being an real life dataset, consisted of the following issues: Was not uniformly populated for each EV during the time range. Some EVs had data for 6 months, while some EVs had data for just 3-4 hours.

Methodology:
rted by deep diving into the dataset with two EDAs to understand the dataset better and explore factors that could be impacting the energy consumption of an individual car.

Some interesting insights from the EDA performed:

EDA Part 1: https://public.flourish.studio/story/1113717/

EDA Part 2: https://public.flourish.studio/story/1113715/

Please refer to EV Consumption PDF attached to see the EDA summary and Modeling Approach. 

Equipped customers with insights about their EVs Hourly energy consumption and helped predict future charging behavior. Created energy consumption-wise clusters and LSTM model for future consumption insights. Designed sample dashboard views with insights and recommendations for customers.
