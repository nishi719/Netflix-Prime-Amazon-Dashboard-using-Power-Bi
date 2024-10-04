# Netflix-Prime-Hotstar Dashboard (Power BI)
This project is an all-inclusive Power BI dashboard that analyzes content on three major streaming platforms: Netflix, Amazon Prime, and Hotstar. The datasets used were sourced from Kaggle and contain information about all movies and TV shows available on these platforms. The main aim of this project is to derive meaningful insights and perform comparative analysis of content across the platforms using interactive visualizations.

## Key Features:
- Content Summary: Count the total number of movies and TV series on each platform.
- Genre Report: Report the top genres and percent share for all platforms.
- Year-wise Trends: Observe the pattern of content published year by year.
- Rating & Popularity: Analyze rating distribution on each platform and their corresponding popularity metric.
- Platform-specific Insights: Discover each platform's unique contents, trends, and patterns.

## Dataset (Kaggle)
The datasets used for this analysis are:
- Netflix Data (https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Amazon Prime Data (https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)
- Hotstar Data (https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows)

## Steps to Prepare Power BI Dashboard
 1. Data Collection
Download the datasets for Netflix, Amazon Prime, and Hotstar from Kaggle.
Review and clean the data, handling missing values and inconsistencies.

 2. Data Preprocessing
Import the datasets into Power BI.
Apply Power Query to clean the data: filter rows, remove duplicate records, replace null values, and transform columns where applicable, such as separating movies from TV shows and normalizing dates.

3. Data Modeling
Connect different datasets through common attributes like genres or release years if required.
Implement Calculated Columns and Measures in Power BI to compute insights like total content per year, average ratings, or total content per genre.
Build aggregations so that data can be summarized for easy visualization.

4. Data Visualization
Rich visualizations are achieved through various types of Power BI charts such as bar charts, pie charts, line charts, and stacked column charts.
Slicers enable dynamic filtering by genres, release years, ratings, and platforms to enhance the dashboard's interactivity.
Cross-filtering allows all related data across visuals to update when interacting with one visualization.
Tooltips and Conditional Formatting highlight key points by using colors and providing additional information upon hover.

5. Interactive Features
Genre Slicers: Filter by genres across all three platforms.
Year Slicers: Analyze trends and release patterns for specific years.
Platform Filters: Compare the content libraries of Netflix, Amazon Prime, and Hotstar.
Dynamic KPIs: Instantly view total content, most popular genres, and top-rated shows per platform.

6. Formatting & Optimization
Apply consistent formatting to ensure a clean, professional appearance. The color scheme is aligned with the respective platform branding (e.g., Netflix red, Prime blue, Hotstar yellow). Labels, legends, and data points are clearly visible for easy understanding.
Use data reduction techniques like filtering unnecessary records and reducing granularity where detailed analysis is not needed to enhance performance.
Define hierarchies (e.g., years, months) to enable drill-down capabilities in time-based visuals.

7. Dashboard Export & Publishing
Export the dashboard to Power BI Service for real-time sharing.
Export the report to formats such as PDF and PowerPoint for presentations.


## How the .pbix File Works
The core project file in Power BI is the .pbix file, which contains:

- Data Sources: The datasets are stored within the .pbix file. When opened, Power BI reads and displays the prepared data.
- Power Query Transformations: Any data cleaning or manipulation done in Power Query (e.g., filtering, merging, adding columns) is embedded into the file.
- Data Model: The file includes relationships between tables, calculated fields (e.g., total counts, averages), and aggregations for slicing and dicing the data.
- Visualizations and Layouts: All dashboard visuals (charts, graphs, tables) and interactivity features (slicers, filters, drill-down capabilities) are embedded within the .pbix file.
- DAX Queries: Calculations using DAX (Data Analysis Expressions) for KPIs, measures, and comparisons are saved and can be recomputed on-demand.

## Interacting with the .pbix File
You can interact with the .pbix file directly in Power BI Desktop by:
- Modifying Visuals: Adjusting the charts, tables, and filters to explore specific aspects of the data.
- Customizing Calculations: Adding or editing calculated fields, measures, or relationships between tables.
- Data Refreshing: Refresh the file to load the latest data when the datasets are updated.

## How to Use the Dashboard

- Clone or download the project files from this repository.
- Open the Power BI .pbix file in Power BI Desktop to explore the dashboard.
- Use the interactive elements such as slicers and filters to view content by different genres, years, platforms, and ratings.


