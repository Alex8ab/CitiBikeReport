# tableau-challenge
Data story vizualization using City Bike NYC Data

**Link to Tableau Public Story:** [City Bike Report 2020](https://public.tableau.com/profile/alejandro.ochoa1874#!/vizhome/CitiBikeNJCReport2020/CitiBikeStory)

**Data Source:** [Citi Bike System Data](https://www.citibikenyc.com/system-data)

![Tableau gif](https://media.giphy.com/media/GQyK6ywwQ8Wvw8psGk/giphy.gif)

**Objective:** 
Look up in data logs in the NJC Citi Bike Trip History Logs and design visualizations for discovered phenomena. The timespan chose is January 2020 to December 2020.

**ETL:** 
-	Extracted data from Citi Bike System Data from January to December 2020
-	Append each csv file to a combined dataset
-	Replace the Gender variables of 0, 1, 2 to Unknown, Male, and Female
-	Created and saved this dataset into a csv file 
-	Loaded dataset into a Tableau Workbook

A phenomenon that is very interesting is that the top user by age is 52 years-old and not a range of ages (i.e. 50-55 years) who decided not to show their gender, this group has a the most trips made with an average of 58 min of duration and most of their trips start in Liberty Light Rail and Newport Pkwy very near to NYC. This group moves all the averages and trends in a huge way.

**Analysis:** 

- Total Number of Trips: 336,802
- Average Trip Duration: 26.25 minutes
- Top User by Age Group: Millennials (24-39 years)
- Top User by Age: 52 years
- Top User by Gender: Men
- Top User by Customer Type: Subscriber

**Trips Description:**

Most trips were made by 52 years old users who decided not to show their gender and average a 59-minute ride. There were more men than women who used the service and in average Generation Z made the longer trips.

**Rider Demographics:**

Most trips were made by 52 years old users who decided not to show their gender and average a 59-minute ride. There were more men than women who used the service and in average Generation Z made the longer trips.

**Peak Times:**

All age groups had the hourly peak at 6:00 p.m. and the second higher hourly peak was at 8:00 a.m. except for Generation Z which had not school.
The highest peak by day was Saturday except for Baby Boomers Generation which was Wednesday.

**Popular Stations:**

The four most popular stations were Grove St. PATH, Newport Pkwy, Liberty Light Rail and Hamilton Park and three of them are near NYC.

**Ridership Growth:**

The peak hour in Q1 was 8:00 a.m. but in Q2 the number of trips fell drastically, especially those made at that time and increased during office hours. This can be explained by the effect of the pandemic since people stopped going to the office and began to manage their own time. The trips decreased in Q1 and increased in the summer when some restrictions were relaxed and again decreased in winter with the 2nd wave.
