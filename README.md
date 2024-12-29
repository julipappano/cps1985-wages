# CPS1985
This repository contains an analysis of the CPS1985 dataset, conducted using R and RMarkdown. The analysis explores key factors influencing wages, leveraging descriptive statistics, data visualizations, and regression modeling to derive insights.

## Project Overview
The goal of this project is to:
* Analyze wage determinants such as education, age, and work experience.
* Visualize data distributions and relationships using histograms, boxplots, and scatterplots.
* Investigate regression models and account for omitted variable bias (OVB).

## Dataset Description
The CPS1985 dataset comprises 534 observations from the U.S. Current Population Survey conducted in 1985. Key variables include:
* Wage: Hourly earnings (USD).
* Education: Total years of education.
* Experience: Years of professional experience.
* Age: Worker age (years).
* Additional variables: Gender, ethnicity, occupation, sector, union membership, and marital status.

## Key Insights
### Descriptive Statistics:
* Median hourly wage: $7.78.
* Workers' median age: 35 years.
* Median levels of education and experience: 12 years and 15 years, respectively.
* Wages and experience distributions are skewed to the right, indicating a concentration of lower values with some high-value outliers.

### Visualizations:
* Histograms and Boxplots: Show data spread, central tendencies, and skewness for variables like wages, education, and experience.
* Scatterplots: Highlight relationships between variables, such as the positive correlation between age and experience.

### Regression Analysis:
* Three regression models explore how education and age influence wages.
* Omitted variable bias (OVB) is identified and quantified, showcasing the importance of including related predictors.

## Prerequisites
To replicate the analysis, ensure you have the following:
* R (version 4.0 or higher)
* RStudio
* Required R packages:
  * tidyverse
  * ggplot2
  * dplyr
  * knitr
  * markdown

Install all required packages using:
install.packages(c("tidyverse", "ggplot2", "dplyr", "knitr", "markdown"))

## Author
Julieta Pappano

Data Analyst and Public Policy Specialist, with a keen interest in leveraging data analysis to address policy and economic challenges.
