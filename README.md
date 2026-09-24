# econ3916-lab03-visualization
# Honest vs. Misleading Visualizations

## Objective

This project explores how visualization choices can change the way economic data is interpreted and demonstrates the importance of using honest, well-designed visualizations alongside exploratory data analysis.

## Methodology

- Recreated Anscombe's Quartet to compare four datasets with nearly identical summary statistics but very different visual patterns.
- Calculated the Lie Factor for a truncated-axis revenue chart and redesigned the visualization to more accurately represent the true change in the data.
- Analyzed FRED average hourly earnings data in both nominal and inflation-adjusted 2020 dollars.
- Created four different visualizations of the same real wage data to examine how choices such as axis limits, time periods, and log scales can change the story presented by a chart.
- Conducted a four-step EDA process on World Bank GDP data covering 262 economies and 64 years, examining structure, distributions, relationships, and anomalies.
- Used a log transformation to better visualize the highly right-skewed distribution of GDP values.
- Built an interactive honest-chart toggler that allows users to change the wage series, y-axis floor, time period, and scale while displaying a live Lie Factor.

## Key Findings

Anscombe's Quartet showed that nearly identical summary statistics can hide completely different patterns in the underlying data, showing why visualization should be an important part of the analysis process. The truncated-axis revenue chart produced a Lie Factor of 49.0, meaning a 4.1% increase was visually presented as a 200% increase. The wage analysis also showed how changing the y-axis, time period, or scale can significantly change how the same data appears. Comparing nominal and real wages demonstrated the importance of adjusting for inflation when comparing purchasing power across decades. Finally, the World Bank GDP analysis showed that GDP is extremely right-skewed and that a log transformation makes differences across economies much easier to analyze.
