# Investigating EV charging data


**Introduction:**

Got an opportunity to work with a home energy consumption monitoring technology company through XN project at Northeastern University from Oct 2021 to Dec 2021 whose goal is to help customers understand their household energy consumption, device charging habits, and ultimately reduce their energy footprint and help customers save money.

**Business Objective:**

1) To predict based on past charging behavior for a car when and how much energy would a car consumes at a Household.
2) Equip customers with insights on the energy consumption by their EVs and recommend how the customer could save money or make better choices with their EV charging behavior. 
3) So, the goal of the project is to understand charging patterns and recommend when the customer should charge their EV.

**Dataset summary**
1) Dataset provided consisted of ~1200 Households across the USA with one or more EVs of various brands for each Household. 
2) For each EV hourly energy consumption was provided. 
3) Columns: House number, State, Zip3, Time, EV0:EV3
4) Rows: 370K
5) Issues: Being an real-life dataset, data was not uniformly populated for each EV during the time range. Some EVs had data for 6 months, while some EVs had data for just 3-4 hours.

![image](https://user-images.githubusercontent.com/10954081/155168938-8907a009-5c14-41b9-8043-5437458cab40.png)

**Problem Challenges:**

Hourly EV consumption is impacted by
1) Car Model: Each Car model can have a different battery capacity and time to charge.
2) Car Utility: A customer may be driving every day to work or another customer might be taking out the car only once a week to do nearby shopping, so utilization of the battery life and charging needs may vary. Also it may be possible that some customers charge their cars every day even from 80% to 100% and another customer may be charging their car only when the battery level reaches 10%.
3) Geo location: Customer’s location may impact car utility. Staying in remote areas or having limited charging stations in the vicinity might lead the customer to drive longer distances every day and may end up needing to charge the car more often.
4) Weather: Conditions may impact the Charging pattern like the extreme environments may impact the battery capacity or battery usage
5) Charging pattern: Some cars may charge 50% in 30 minutes and may take another hour for the remaining 50% charge. On the other hand, another car might need 1 hour to charge 50% of the battery and another 1 hour for the remaining 50%.
6) Battery degradation: As in any electronic device over time the charging pattern may change, and capacity might degrade leading to longer charging times and higher energy consumption.

Please refer to EV Consumption PDF attached in the repository to see the EDA summary, Modeling Approach, and Results. Designed sample dashboard views with insights and recommendations for customers as part of the EV consumption Presentation PDF.

To see solutions and visuals refer to EV consumption

EDA Part 1: https://public.flourish.studio/story/1113717/

EDA Part 2: https://public.flourish.studio/story/1113715/
