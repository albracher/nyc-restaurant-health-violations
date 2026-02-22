> **Note:** Data can be found [here](https://drive.google.com/drive/folders/1LtOxQhLu87fNq7LRlwUEXhwXtVUu1uTP?usp=sharing), cannot upload files >25MB to GitHub:

# NYC Restaurant Inspections Data Analysis
## Project Overview
This project was a data analysis of NYC restaurant inspection records in order to identify health violation trends across different cuisines and boroughs. This was the first project we did as part of the fellowship, and focuses on data cleaning, exploratory data analysis, and visualizing critical health risks.

## What was used?
I used R to do this project, my groupmates used Excel mainly. In regards to libraries, I used tidyverse, lubridate, tidymodels, writexl, and showtext.

## What was my workflow?
We started by discussing the data together, as a group. From there:
I first loaded the data by importing the raw NYC restaurant inspection records.
From there, data was cleaned using drop_na() to handle missing values and distinct() to remove duplicate entries.

In regards to exploratory analysis, I used glimpse() as well as summary() to understand column distributions and data types.

## Key Insights
* Inspection Volume by Borough: Manhattan accounts for the highest percentage of inspections (38.8%), followed by Brooklyn (24.5%) and Queens (23.2%).
* Cuisine Trends: American (29,969), Chinese (15,325), and Pizza (9,200) are the most frequently inspected restaurant types.
* Health Grades: Approximately 80% of restaurants across all boroughs achieved an 'A' grade.
* Violation Severity: Critical flags were issued in approximately 47.5% of total inspections.

## What else is there?
The slides for the final presentation we used can be found [here](https://docs.google.com/presentation/d/1nAZIt5aypFEWZLDAQf2s2_rSrfliFsphiZwLjUY9-x4/edit?usp=sharing).
