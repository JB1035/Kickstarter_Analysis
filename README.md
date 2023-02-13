# Kickstarting with Excel

## Overview of Project

Analysis to help upcoming playright, Louise, get funding for her play "Fever." She's estimating a budget of over $10,000 and is understandably hesitant about jumping into her first fundraising campaign. The goal is to use Excel to organize, sort, and analyze crowdfunding data to determine whether there are specific factors that make a project's campaign successful.

### Purpose

Use the insights to analyze current site data which can help Louise better understand campaigns from start to finish, in order to set up her campaign to mirror other successful ones in the same category. 

## Analysis

Using the keyboard shortcut command + down arrow, we were quickly able to see this was a large data set with over 4k rows. Givent this stat, we decided to use pivot tables to more thoroughly correlate this data. Additionally visulzatons, specifically line graphs, allowed us to determine trends across time.

### Outcomes Based on Launch Date

![This is an image](Resources/Theater_Outcomes_vs_Launch.png)

### Outcomes Based on Goals

![This is an image](Resources/Outcomes_vs_Goals.png)

### Challenges Encountered

Some challenges in working with the data was that it needed to be organized and sorted before taking on any type of anlaysis. This was done by:

* Separating the parent categories and subcategories into seperate columns.
* Converting the "Deadline" and "Launched_at" column formats from a Unixm timestamp into a day-month-year format that we can interpret within a new column called "Date Created Conversion." This represents actual time of the campaign launch.
* The overall date range across the entire data set is to sparse and needed to be reduced to a more manageable subset for better analysis - this was be done by adding a new column called "year" to extract the year from the date converted column. This allowed to us to gather more data for each month in the year, across all parent and subcategory columns for the pivot tables.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
