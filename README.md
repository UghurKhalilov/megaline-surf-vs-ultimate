# Megaline Revenue Analysis

## Overview
This project analyzes the behavior and revenue of 500 Megaline telecom 
customers across two prepaid plans: Surf and Ultimate. The goal is to 
determine which plan generates more revenue to help the commercial 
department adjust the advertising budget.

## Dataset
The analysis is based on five tables covering customer profiles, 
call records, text messages, internet sessions, and plan details 
for the year 2018.

## Methodology
- Data cleaning: type conversion, rounding call durations, handling missing values
- Monthly usage aggregation per user (calls, messages, data)
- Revenue calculation based on plan limits and overage charges
- Descriptive statistics and visualizations (histograms, box plots, bar charts)
- Independent samples t-test for hypothesis testing

## Key Findings
- Ultimate plan users rarely exceed their generous limits, consistently 
  paying the fixed $70 monthly fee with minimal variance
- Surf plan users frequently exceed their limits, generating variable 
  revenue above the $20 base fee
- Both statistical hypotheses were rejected (p-value = 0.0000):
  - Ultimate plan generates significantly higher revenue than Surf
  - NY-NJ region users show significantly different revenue compared 
    to users from other regions

## Recommendation
The Ultimate plan is more profitable per user. Advertising budget 
should prioritize promoting the Ultimate plan, with special focus 
on high-revenue regions like NY-NJ.

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Plotly, SciPy

## View Notebook
For interactive visualizations, view the notebook on 
[nbviewer](https://nbviewer.org/github/UghurKhalilov/megaline-surf-vs-ultimate/blob/main/megaline.ipynb)
