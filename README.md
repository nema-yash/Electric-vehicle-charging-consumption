# Investigating EV charging data


**Introduction:**

Got an opportunity to work with a home energy consumption monitoring technology company through XN project at Northeastern University from Oct 2021 to Dec 2021 whose goal is to help customers understand their household energy consumption, understand their habits, and ultimately reduce their energy footprint and save money.

**Business Objective: **

1) To predict based on past charging behavior for a car when and how much energy would a car consume at a Household.
2) Equip customers with insights on the energy consumption by their EVs and recommend how the customer could save money or make better choices with their EV charging behavior. 
3) So, the goal of the project is to understand charging patterns and recommend when the customer should charge their EV.

**Dataset summary**
1) Dataset provided consisted of ~1200 Households across the USA with one or more EVs of various brands for each Household. 
2) For each EV hourly energy consumption was provided. 
3) Columns: House number, State, Zip3, Time, EV0:EV3
4) Issues: Being an real life dataset, data was not uniformly populated for each EV during the time range. Some EVs had data for 6 months, while some EVs had data for just 3-4 hours.

![image](https://user-images.githubusercontent.com/10954081/155168938-8907a009-5c14-41b9-8043-5437458cab40.png)

**Problem Challenges:**

Hourly EV consumption is impacted by
•	Car Model: Each Car model can have a different battery capacity and time to charge.
•	Car Utility: A customer maybe driving every day to work or another customer might be taking out the car only once a week to do nearby shopping, so utilization of the battery life and charging needs may vary. Also it maybe possible that some customers charge their cars everyday even from 80% to 100% and another customer may be charging their car only when battery level reaches 10%.
•	Geo location: Customer’s location may impact car utility. Staying in remote areas or having limited charging stations in the vicinity might lead the customer to drive longer distances everyday and may end up needing to charge the car more often.
•	Weather: Conditions may impact the Charging pattern like the extreme environments may impact the battery capacity or battery usage
•	Charging pattern: Some cars may take charge 50% in 30 minutes and may take another hour for the remaining 50% charge. On the other hand, another car might need 1 hour to charge 50% of the batter and another 1 hour for the remaining 50%.
•	Battery degradation: As in any electronic device over time the charging pattern may change, and capacity might degrade leading to longer charging times and higher energy consumption.

Please refer to EV Consumption PDF attached to see the EDA summary and Modeling Approach.

To see solution and visuals refer to EV consumption
EDA Part 1: https://public.flourish.studio/story/1113717/

EDA Part 2: https://public.flourish.studio/story/1113715/

 

Equipped customers with insights about their EVs Hourly energy consumption and helped predict future charging behavior. Created energy consumption-wise clusters and LSTM model for future consumption insights. Designed sample dashboard views with insights and recommendations for customers.
