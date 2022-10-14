# Cyclistic-bike-share-analysis

## Process

Then, process your data for analysis using the following Case Study Roadmap as a guide:

Guiding questions

1. What tools are you choosing and why? 
2. Have you ensured your data’s integrity? 
3. What steps have you taken to ensure that your data is clean? 
4. How can you verify that your data is clean and ready to analyze? 
5. Have you documented your cleaning process so you can review and share those results?

Key tasks

1. Check the data for errors.
2. Choose your tools.
3. Transform the data so you can work with it effectively.
4. Document the cleaning process.

Deliverable

Documentation of any cleaning or manipulation of data

Follow these steps:

1. Download the previous 12 months of Cyclistic trip data.
2. Unzip the files.
3. Create a folder on your desktop or Drive to house the files. Use appropriate file-naming conventions.
4. Create subfolders for the .CSV file and the .XLS or Sheets file so that you have a copy of the original data. Move the downloaded files to the appropriate subfolder.
5. Follow these instructions for either Excel (a) or Google Sheets (b):a. Launch Excel, open each file, and choose to Save As an Excel Workbook file. Put it in the subfolder you created for .XLS files. b. Open each .CSV file in Google Sheets and save it to the appropriate subfolder.
6. Open your spreadsheet and create a column called “ride_length.” Calculate the length of each ride by subtracting the column “started_at” from the column “ended_at” (for example, =D2-C2) and format as HH:MM:SS using Format > Cells >Time > 37:30:55.
7. Create a column called “day_of_week,” and calculate the day of the week that each ride started using the “WEEKDAY” command (for example, =WEEKDAY(C2,1)) in each file. Format as General or as a number with no decimals, noting that 1 = Sunday and 7 = Saturday.
8. Proceed to the analyze step.