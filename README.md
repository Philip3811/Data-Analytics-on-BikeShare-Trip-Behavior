# Data Analytics on Bikeshare Trip Behavior

## Project Overview
This project analyzes behavioral differences between casual riders and annual members
using a cleaned sample of 15,000 trips from an urban bikeshare system. The analysis
integrates exploratory data analysis, statistical hypothesis testing, and predictive
modeling to identify meaningful patterns in trip duration, timing, and usage behavior.

The goal is to understand how rider behavior differs across user types and to derive
actionable insights for system planning, pricing optimization, and targeted marketing.

## Data & Preprocessing
The raw bikeshare data was cleaned and processed before analysis. Key preprocessing
steps included:
- Trip filtering and outlier removal
- Haversine distance calculation
- Feature engineering for day-of-week and time-of-day usage

Due to size and licensing considerations, raw and processed datasets are not included
in this repository.

## Analytical Methods
- Exploratory data analysis and visualization
- Welch’s t-tests for group mean comparisons
- Chi-square tests for categorical associations
- Multivariable logistic regression to model rider type

## Key Findings
- Casual riders take significantly longer trips on average
- Casual usage is concentrated on weekends and afternoon hours
- Annual members exhibit shorter, more consistent weekday commuting patterns
- Distance differences become negligible after robustness checks

These results demonstrate clear behavioral segmentation between rider types.

## Tools & Technologies
- R
- tidyverse
- ggplot2
- geosphere
- broom
- Jupyter Notebook
