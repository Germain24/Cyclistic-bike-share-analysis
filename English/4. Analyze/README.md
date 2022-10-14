# Cyclistic-bike-share-analysis

## Analyze

Now that your data is stored appropriately and has been prepared for analysis, start putting it to work. Use the following Case
Study Roadmap as a guide:

Guiding questions

1. How should you organize your data to perform analysis on it? 
2. Has your data been properly formatted? 
3. What surprises did you discover in the data? 
4. What trends or relationships did you find in the data? 
5. How will these insights help answer your business questions?

Key tasks

1. Aggregate your data so it’s useful and accessible.
2. Organize and format your data.
3. Perform calculations.
4. Identify trends and relationships.

Deliverable

A summary of your analysis

Follow these steps for using spreadsheets

Open your spreadsheet application, then complete the following steps:
1. Where relevant, make columns consistent and combine them into a single worksheet.
2. Clean and transform your data to prepare for analysis.
3. Conduct descriptive analysis.
4. Run a few calculations in one file to get a better sense of the data layout. Options:
   1. Calculate the mean of ride_length 
   2. Calculate the max ride_length 
   3. Calculate the mode of day_of_week
5. Create a pivot table to quickly calculate and visualize the data. Options:
   1. Calculate the average ride_length for members and casual riders. Try rows = member_casual; Values = Average of ride_length. 
   2. Calculate the average ride_length for users by day_of_week. Try columns = day_of_week; Rows = member_casual; Values = Average of ride_length. 
   3. Calculate the number of rides for users by day_of_week by adding Count of trip_id to Values.
6. Open another file and perform the same descriptive analysis steps. Explore different seasons to make some initial observations.
7. Once you have spent some time working with the individual spreadsheets, merge them into a full-year view. Do this with the tool you have chosen to use to perform your final analysis, either a spreadsheet, a database and SQL, or R Studio.
8. Export a summary file for further analysis.

Follow these steps for using SQL

Open your SQL tool of choice, then complete the following steps:
12. Import your data.
13. Explore your data, perhaps looking at the total number of rows, distinct values, maximum, minimum, or mean values.
14. Where relevant, use JOIN statements to combine your relevant data into one table.
15. Create summary statistics.
16. Investigate interesting trends and save that information to a table.

Follow these steps for using R

Open R Studio and use this script to complete the following steps:
17. Import your data.
18. Make columns consistent and merge them into a single dataframe.
19. Clean up and add data to prepare for analysis.
20. Conduct descriptive analysis.
21. Export a summary file for further analysis.