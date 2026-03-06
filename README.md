# NYC Taxi Ride Analytics Dashboard

An exploratory data analysis and interactive visualization of 1M+ NYC taxi trips from January 2022, uncovering demand patterns and fare trends across days and hours.

---

## Overview

New York City generates millions of taxi trips every month. This project digs into January 2022 trip data to answer a simple question: when and where does taxi demand — and fare pricing — peak? The results include at least one surprising finding.

---

## Objectives

- Clean and analyze a large real-world dataset of NYC taxi trips
- Identify patterns in ride duration and fare amounts across days of the week and hours of the day
- Build an interactive dashboard that makes temporal trends easy to explore

---

## Key Findings

- **Highest average fares occurred on Fridays at 11am** — a counterintuitive result, as late-night weekend hours might be the expected peak
- Ride duration varied meaningfully by day of the week, suggesting different usage patterns on weekdays vs. weekends
- The interactive dashboard makes it easy to spot hour-by-hour fare shifts that would be invisible in static charts

---

## Visualizations

### 1. Average Ride Duration by Day of Week
A bar chart showing how average trip length varies across Monday–Sunday, revealing weekly demand rhythms.

### 2. Interactive Fare Dashboard
A dynamic chart with a time-of-day slider (0–23 hours) displaying average total fare for each hour, broken out by day of the week. Allows users to scrub through the day and watch fare patterns shift in real time.

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data cleaning and aggregation |
| Plotly | Interactive visualizations and slider widget |
| Jupyter Notebook | Analysis environment |

---

## Dataset

- **Source:** NYC Taxi & Limousine Commission (TLC) Trip Record Data
- **Scope:** January 2022, Yellow Taxi trips
- **Size:** 1M+ records
- **Fields used:** pickup datetime, trip duration, total fare amount
- Raw data not included in this repo due to file size. Available publicly at [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page).

---

## What I Learned

Working with a million-row dataset required careful attention to data cleaning and efficient aggregation before any analysis was possible. The unexpected Friday 11am fare peak is a good reminder that assumptions about urban behavior don't always hold — and that exploratory analysis is worth doing thoroughly before jumping to conclusions.
