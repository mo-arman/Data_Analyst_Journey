# Data_Analyst_Journey

## Matplotlib Practice & Data Visualization Guide

This repository contains hands-on practice, examples, and mini exercises for learning Matplotlib from basic to intermediate level. The goal is to understand how data visualization works in real analytics workflows.

# What is Matplotlib?

Matplotlib is a Python library used for creating static, animated, and interactive visualizations. It is widely used in:

Data Analytics

Machine Learning

Data Science projects

Reporting dashboards

Exploratory Data Analysis (EDA)

It helps convert raw data into visual insights like graphs and charts.

# Topics Covered
1. Basic Plotting

Line charts

Axis labeling

Titles

Grid and layout

2. Bar Charts

Category comparison

Vertical and horizontal bars

Real-life data visualization

3. Pie Charts

Percentage distribution

Category share analysis

4. Scatter Plots

Relationship between variables

Correlation analysis

Pattern identification

5. Histograms

Data distribution

Frequency analysis

Outlier detection

6. Plot Customization

Colors

Markers

Line styles

Legends

7. Multiple Plots

Subplots

Comparing multiple datasets

8. Working with Real Data

CSV files

Pandas integration

Data cleaning + visualization

Installation

Install matplotlib using pip:

pip install matplotlib

For Jupyter Notebook:

!pip install matplotlib
Basic Example
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 20, 15, 25, 30]

plt.plot(x, y)
plt.title("Simple Line Chart")
plt.xlabel("X values")
plt.ylabel("Y values")
plt.show()
Practice Exercises
Exercise 1

Create a line chart of daily study hours for one week.

Exercise 2

Create a bar chart of monthly expenses:

Food

Travel

Recharge

Shopping

Exercise 3

Create a scatter plot:
Hours studied vs marks scored.

Exercise 4

Create a histogram:
Random numbers between 1–100.

Real Use Cases

Matplotlib is used in:

Sales analysis

Stock market visualization

Student performance tracking

Business dashboards

Data science model evaluation

Project Goal

This repository is focused on learning by doing:

Writing plotting code

Understanding visualization logic

Building analyst mindset

Preparing for real data analytics projects

Next Learning Steps

After Matplotlib:

Seaborn (advanced visualization)

Pandas plotting

Real dataset analysis

Dashboard tools (Power BI / Tableau)

Machine learning visualization

Author

Arman
Data Analytics Learner | Python | SQL | Visualization