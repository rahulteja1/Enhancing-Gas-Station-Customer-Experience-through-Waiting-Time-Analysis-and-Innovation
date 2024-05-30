# Enhancing Gas Station Customer Experience through Waiting Time Analysis and Innovation

## Project Overview

This project aims to improve customer satisfaction at gas stations in Houghton by analyzing and reducing customer waiting times. We conducted a comprehensive statistical analysis using Two-way ANOVA to understand the impact of various factors on waiting times and proposed strategies to mitigate them.

## Data Description

The dataset includes customer waiting times from multiple gas stations in Houghton, categorized by:
- **Gas_station**: Name of the gas station
- **Car_type**: Type of vehicle (e.g., pickup truck, sedan, SUV)
- **Day**: Day of the week
- **No_pumps**: Total number of gas pumps
- **In_time**: Vehicle entry time
- **Out_time**: Vehicle exit time

## Methodology

### Data Collection and Cleaning
- **Sampling**: Random sampling of gas stations in Houghton to ensure representativeness.
- **Data Cleaning**: Removal of outliers, such as extreme waiting times due to non-refueling activities (e.g., having meals in cars).

### Analysis
- **Two-way ANOVA**: Analyzed the effects of `Gas_station` and `Car_type` on `Waiting_time`.
- **Visualization**: Used box plots and bar plots to illustrate differences in waiting times and validate assumptions.

## Statistical Analysis

### Hypotheses
- **Null Hypotheses (H0)**:
  - H01: No significant difference in waiting times across gas stations.
  - H02: No significant difference in waiting times among car types.
  - H03: No significant interaction between gas station and car type on waiting times.
- **Alternative Hypotheses (Ha)**:
  - Ha1: Significant difference in waiting times across gas stations.
  - Ha2: Significant difference in waiting times among car types.
  - Ha3: Significant interaction between gas station and car type on waiting times.

### Results
- **Main Effects**: Car type significantly impacts waiting time, with pickup trucks experiencing longer waits compared to sedans and SUVs.
- **Interaction Effects**: No significant interaction between gas station and car type.
- **Pairwise Comparisons**: Conducted using Tukey's HSD to identify specific group differences.

### Assumptions Check
- **Homogeneity of Variance**: Verified using residual plots.
- **Normality**: Checked using Q-Q plots.

## Visualizations
- **Box Plots**: Displayed waiting time distribution across gas stations and car types.
- **Bar Plots**: Illustrated average waiting times for different car types and gas stations.
- **Interaction Plot**: Showed mean waiting times for car types across gas stations.

## Conclusion
The study found that vehicle type significantly affects waiting times, with pickup trucks facing the longest waits. This suggests the need for tailored management strategies to accommodate larger vehicles more efficiently. While no significant interaction between gas station location and car type was observed, further research could explore additional factors like staffing levels and operational procedures.

## References
- [Two-way ANOVA test in R](http://www.sthda.com/english/wiki/two-way-anova-test-in-r#what-is-two-way-anova-test)
- [Investopedia - ANOVA](https://www.investopedia.com/terms/a/anova.asp)
- [Ademos - Chapter 12](https://ademos.people.uic.edu/Chapter12.html)
- [Scribbr - ANOVA in R](https://www.scribbr.com/statistics/anova-in-r/)

