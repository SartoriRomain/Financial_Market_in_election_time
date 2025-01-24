Project README

Project Overview

This project focuses on the analysis of financial indices during specific political mandates. The main objectives are:

Compare the evolution of financial indices during Obama’s mandate (2013) and Trump’s first mandate (2017).

Analyze whether Trump’s current mandate (2025) follows trends observed in previous mandates.

Key datasets include financial index data spanning these periods, with details on opening, closing, highest, and lowest prices, as well as trading volumes.

Features

Data Cleaning and Preparation

Standardization of data formats (e.g., datetime for dates, float for financial values).

Addition of a Mandate column to distinguish between Obama (2013), Trump 1 (2017), and Trump 2 (2025).

Analysis Objectives

Evolution of financial indices over time.

Comparison of trends between mandates.

Identification of correlations between financial indices and political events.

Visualizations in Power BI

Line Charts: To observe index performance over time.

Stacked Bar Charts: To compare trading volumes by mandate and index.

Heatmaps: To identify patterns in market activity by week or month.

Scatter Plots: To correlate volume and price volatility.

Requirements

Python

Libraries: pandas, numpy, matplotlib (for preliminary analysis).

Power BI

For advanced data visualization and dashboards.

How to Use

Prepare the Data:

Use the Python script provided to clean and preprocess the raw datasets.

Ensure the Mandate column is correctly assigned based on the date ranges for each mandate.

Load Data into Power BI:

Import the cleaned datasets into Power BI.

Ensure relationships between tables (if multiple) are correctly established.

Create Visualizations:

Use provided templates or instructions to replicate key visualizations.

Explore additional insights using filters for indices, mandates, or date ranges.

