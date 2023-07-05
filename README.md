# Road Accident Dashboard

This project aims to create a comprehensive dashboard using Tableau to analyze road accident data. The dashboard provides key performance indicators (KPIs) for total accidents, casualties, fatal casualties, serious casualties, and slight casualties. It also includes year-on-year (YoY) comparisons for the current year and sparklines to visualize the trend over time and donut charts, map charts for representing casualties due to various factors.

## Project Overview

The road accident dashboard utilizes a dataset containing accident records. The main components of the dashboard include:

1. **KPIs**: KPI cards are displayed for total accidents, total casualties, fatal casualties, serious casualties, and slight casualties. These cards provide the current year's values, year on year increase values and visually compare them to the previous year using sparklines.

2. **Parameters**: Parameters are used to select the current year, previous year, and accident severity. The dashboard dynamically adjusts the displayed data based on the parameter selections.

3. **Casualties by Vehicle Type**: This component presents vehicle symbols representing different vehicle types, the number of casualties and provides YoY comparisons based on the selected accident severity and current year.

4. **Casualties by Weather Condition**: A donut chart visualizes the distribution of casualties based on weather conditions. The chart dynamically changes based on the selected accident severity and current year.

5. **Casualties by Road Surface**: Similar to the casualties by weather condition, this donut chart shows the distribution of casualties based on road surface conditions. The chart adjusts dynamically based on the selected accident severity and current year.

6. **Casualties by Road Type**: A bar chart displays the number of casualties categorized by road types. The chart changes dynamically based on the selected accident severity and current year.

7. **Casualties by Location**: A map chart provides a geographical representation of casualties by location. The chart adjusts based on the selected accident severity and current year.

## Features and Functionality

The road accident dashboard incorporates various Tableau features and functionalities, including:

- **Filters**: The dashboard includes filters to narrow down the displayed data based on accident severity, current year, and other relevant parameters.

- **Parameters**: Dynamic parameters allow users to select the current year, previous year, and accident severity, thereby controlling the displayed data in real-time.

- **Grouping**: Vehicle symbols are used to represent different vehicle types(grouped different vehicle models together based on vehicle type), enhancing the visual representation in the casualties by vehicle type component.

- **Dynamic Titles**: The titles of each chart are dynamically updated based on the selected accident severity.

## Instructions for Use

To utilize the road accident dashboard effectively, follow these instructions:

1. Make sure Tableau Desktop is installed on your system.
2. Open the Tableau project file (.twb) containing the road accident dashboard.
3. Use the provided filters and parameters to select the desired accident severity, current year, and other relevant options.
4. Explore the KPIs, bar charts, donut charts, and map chart to gain insights into road accident data.
5. Observe the sparklines and dynamic titles to understand the YoY trends and context of the displayed data.
6. Interact with the dashboard by adjusting filters and parameters to perform further analysis and investigate specific scenarios.

## Conclusion

The road accident dashboard provides a comprehensive visualization of road accident data. By utilizing Tableau's features such as filters, parameters, grouping, and dynamic titles, users can explore and analyze various aspects of road accidents based on severity, year, and other factors. The interactive nature of the dashboard allows for a deeper understanding of accident patterns, trends, and their impact on casualties.
