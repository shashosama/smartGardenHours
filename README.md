#   Gardening & Air Quality Data Analysis
## General Problem

Gardeners often struggle to determine the best time to plant or care for their plants due to changing environmental conditions. While temperature is commonly considered, **air quality factors like ozone levels are often overlooked**—despite their known impact on plant health and photosynthesis.

However, publicly available air quality data is often complex and not directly usable by non-experts, leaving a gap in **practical gardening advice based on environmental science**.

## Solution

This project explores how environmental air quality impacts plant growth by analyzing real-world datasets using R. It was developed as part of a data science coursework project and includes both the code and report. to:

- Identify how air pollution affects plant health
- Visualize patterns in environmental conditions
- Suggest optimal times of day and year for gardening

By cleaning, merging, and analyzing both datasets in R, we provide **data-driven recommendations** for gardeners on when to plant based on environmental factors.



##  Files

- `daily_44201_2024.csv`: Air quality data (e.g., ozone levels).
- `plant_growth_data.csv`: Observations of plant growth under various conditions.
- `project2R&S.Rmd`: Main R Markdown file with data cleaning, visualization, and analysis code.
- `project2R-S.pdf`: Final rendered PDF report with findings and visualizations.

##  Objectives

- Clean and merge air quality and plant growth datasets.
- Perform exploratory data analysis (EDA).
- Visualize the best time for gardening based on environmental indicators.
- Provide insights to gardeners about ideal planting hours.

## Tools that were Used

- R
- ggplot2
- dplyr
- plotly
- RMarkdown

##  How to Run

1. Open `project2R&S.Rmd` in RStudio.
2. Install required packages if not already installed (`tidyverse`, `plotly`, etc.).
3. Knit the RMarkdown file to generate the final report.
4. 
## What I Learned

This project helped me build practical data science skills and domain knowledge in environmental analytics:

- **Data Cleaning & Integration**: Merged and aligned two separate datasets (air quality and plant growth) using date and location keys.
- **Domain Insight**: Learned how pollutants like ozone can hinder plant development and how to translate scientific metrics into everyday advice.
- **Exploratory Data Analysis**: Used `ggplot2` and `plotly` to create static and interactive visualizations of air quality and plant response trends.
-  **R Workflow Proficiency**: Developed an end-to-end reproducible workflow in RMarkdown—from data ingestion to final report generation.
-  **Communication**: Learned to turn complex environmental data into actionable insights for non-technical users (e.g., home gardeners).


