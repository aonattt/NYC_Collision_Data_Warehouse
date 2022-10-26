# NYC Collision Data Warehouse 
- author(s): Aykut Onat

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: (change this to make applicable to your project)

1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

**Motivation for project:**

The National Highway Traffic Safety Administration just recently has released preliminary estimates of fatal crash fatalities in the US, pointing out the largest fatalities since 2007. The early estimates underline that an estimated 38,680 people died in motor vehicle collisions in 2020. Interestingly, a recent New York Times article points at a spike in fatalities in New York City in 2020. Motor vehicle collisions are among the leading causes of major injuries and accidental death. To cushion and avoid the possible undesired consequences of accidents, more in-depth analysis is needed. The project aims at exploring the datasets chosen, identifying trends, and contributing factors to traffic accidents.

**Description of the issues or opportunities the project will address:**

With 3 datasets provided by NYC Open Data, which is an online repository of data published by NYC agencies, the project aims at finding answers to questions such as

- ​	Where are the crash hotspots?
- ​	What causes accidents the most?
- ​	What time of the day is the safest time to be on the road?
- ​	What type of vehicle causes accidents the most?
- ​	What are the leading factors behind collisions?
- ​	Which seat position is more prone to fatalities in accidents?
- ​	What is the age distribution of people getting involved in an accident?What are the most common damage patterns in collusion?

**Project Business or Organization Value:**

Explore related datasets, identify trends, and contributing factors to traffic accidents happening in NYC.

According to identified trends and contributing factors leading to accidents in this project, measurement suggestions can be made to prevent traffic accidents and lower death tolls more effectively.

**Data Sources:**

1. [NYC Open Data Motor Vehicle Collisions - Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
2. [NYC Open Data Motor Vehicle Collisions – Vehicles](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Vehicles/bm4k-52h4)
3. [NYC Open Data Motor Vehicle Collisions – Person](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Person/f55k-p6yu)

### Business Requirements Definition

List of Data Warehouse KPI's:
1. Number of Accidents by Year per Borough
2. Seasonality of Accidents
3. Effects of Seat Positions and Vehicle Types on Injuries and Fatalities
4. Contributing Factors to an Accident
5. Number of Accidents of Drivers Falling in Each Age Group

### Dimensional Model

This project's Dimensional Model consists of (x) Facts and (y) Dimensions

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Number of Accidents by Year per Borough
  - Grouped Bar Chart of Number of  Accidents per Year by Borough
  - Hot Spots for Crashes Map
2. Seasonality of Accidents
  - Line Graph of Accidents per Month
  - Line Graph of Accidents per Week
  - Line Graph of Accidents per Hourly Interval
3. Effects of Seat Positions and Vehicle Types on Injuries and Fatalities
  - Table of Seat Positions Leading to Injuries and Fatalities
  - Table of Injuries and Fatalities per Person Type
  - Stacked Bar Chart of Vehicle Types Leading to Fatalities
4. Contributing Factors to an Accident
  - Packed Bubble Chart of Contributing Factors to An Accident 
5. Number of Accidents of Drivers Falling in Each Age Group
  - Tree Map of Number of Accidents of Drivers Falling in Each Age Group

### Deployment

The project was deployed on Tableau Public: https://public.tableau.com/app/profile/aykut5620
