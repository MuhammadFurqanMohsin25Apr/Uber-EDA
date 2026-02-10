# Uber Data Exploratory Data Analysis (EDA)

## Project Description

This notebook performs **Exploratory Data Analysis (EDA)** on Uber ride data to understand trip patterns based on **time and frequency of rides**.
The focus of the analysis is on extracting useful features from date-time data and visualizing ride behavior across different time dimensions.

---

## Analyses Performed in the Notebook

The following analyses are included:

### Data Loading and Inspection

* Loaded Uber trip dataset into Pandas DataFrame
* Displayed:

  * First few records
  * Dataset shape
  * Column names
  * Data types
* Checked for missing values

---

### Date-Time Feature Extraction

From the `Date/Time` column, the following features are created:

* **Hour** – to analyze hourly ride frequency
* **Day** – to analyze daily trends
* **Month** – to analyze monthly trends
* **Weekday** – to study weekday vs weekend patterns

---

### Hourly Ride Analysis

* Counted number of rides per hour
* Visualized hourly ride distribution using bar plots
* Identified peak ride hours

---

### Daily Ride Analysis

* Analyzed number of rides per day
* Visualized daily ride counts
* Observed day-to-day fluctuations

---

### Monthly Ride Analysis

* Grouped rides by month
* Visualized ride frequency per month
* Compared demand across months

---

### Weekday Analysis

* Analyzed ride frequency by:

  * Monday to Sunday
* Visualized weekday ride patterns
* Identified busiest weekdays

---

### Combined Time-Based Analysis

* Created pivot tables using:

  * Weekday vs Hour
  * Month vs Hour
* Used **heatmaps** to visualize ride density
* Highlighted peak demand periods

---

## Visualizations Included

* Bar charts for:

  * Hourly ride counts
  * Daily ride counts
  * Monthly ride counts
  * Weekday ride counts
* Heatmaps for:

  * Hour vs Weekday
  * Hour vs Month

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Purpose of Analysis

* Understand user ride behavior
* Identify peak demand times
* Support data-driven decisions for:

  * Driver allocation
  * Pricing strategies
  * Service optimization

---

## File

```
Uber_EDA.ipynb
UberDataset.csv
```

---
