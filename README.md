MATH 608 Final Project
Inflation and Real Personal Income Growth (CPI vs RPI)

This repository contains the final project for CSCI / MATH 608.
The project examines the long-run relationship between inflation and real personal income growth in the United States using a data science workflow.

Project Overview

The goal of this project is to analyze how inflation, measured by the year-over-year growth rate of the Consumer Price Index (CPI YoY), relates to real personal income growth (RPI YoY). Using monthly U.S. data from 1959 to 2020, the project follows the data science lifecycle, including descriptive, exploratory, predictive, and inferential analysis.

Research Questions

The project addresses four types of questions:

Descriptive
What are the distributional characteristics of CPI YoY and RPI YoY over time?

Exploratory
Is there a systematic relationship between inflation and real personal income growth?

Predictive
Can CPI YoY be used to predict RPI YoY using a regression model?

Inferential
Is the effect of CPI YoY on RPI YoY statistically significant based on bootstrap inference?

Data Sources

The data used in this project come from official U.S. government sources:

Federal Reserve Bank of St. Louis (FRED-MD)
Bureau of Economic Analysis (BEA)

The analysis focuses on year-over-year growth rates to avoid non-stationarity and spurious correlations.

Repository Structure

data/
Contains the datasets used in the analysis (CSV or XLSX).

code/
Contains R scripts for data preparation and analysis:

data_cleaning.R

eda_plots.R

regression.R

bootstrap.R

figures/
Contains figures generated from the analysis, including exploratory plots and bootstrap distributions.

reports/
Contains the final written report submitted for the course:

final_report.pdf
