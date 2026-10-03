# 🚕 Uber NYC Data Analysis

> Exploratory Data Analysis of 4.45M+ Uber trip records from New York City using Python.

---

## 📌 Project Overview

This project analyzes Uber trip activity in New York City using Python and Exploratory Data Analysis (EDA).

The goal is to identify patterns in Uber demand across **time, days, Uber bases, and geographic pickup locations** and translate these patterns into practical business insights.

---

## 🎯 Business Objective

The analysis aims to answer questions such as:

- How does Uber trip activity change month-to-month?
- Which hours have the highest recorded trip activity?
- Which days of the week are busiest?
- How does demand vary across different day-hour combinations?
- How is trip activity distributed across Uber bases?
- Where are pickup locations concentrated geographically?

---

## 📊 Dataset

The project uses Uber NYC trip data covering **April to September 2014**.

### Dataset Features

| Column | Description |
|---|---|
| `Date/Time` | Date and time of the trip |
| `Lat` | Pickup latitude |
| `Lon` | Pickup longitude |
| `Base` | Uber base code |

> The raw dataset is not included in this repository because of its large size.

---

## 🧹 Data Cleaning & Preparation

The following data preparation steps were performed:

- Checked dataset structure and data types
- Checked for missing values
- Converted `Date/Time` into datetime format
- Identified and removed duplicate records
- Created time-based features
- Extracted month, day, hour, and day of week

### Data Quality Result

**82,581 duplicate records** were removed.

After cleaning:

**4,451,746 trip records** remained for analysis.

---

## 🔎 Analysis Performed

### 📈 1. Monthly Trip Analysis

Analyzed how recorded Uber trip activity changed from April to September 2014.

### 🕐 2. Hourly Trip Analysis

Analyzed trip activity across the 24 hours of the day.

### 📅 3. Day-of-Week Analysis

Compared recorded trip activity across Monday to Sunday.

### 🔥 4. Day × Hour Heatmap

Used a heatmap to identify patterns across different days and hours.

### 🚗 5. Uber Base Analysis

Compared recorded trip activity across the five Uber bases.

### 📍 6. Geographic Pickup Analysis

Visualized the geographic distribution of Uber pickup locations.

### 🗺️ 7. Pickup Density Analysis

Analyzed areas with higher concentrations of recorded pickup activity.

---

## 📊 Key Findings

| KPI | Result |
|---|---|
| Total Trips | **4,451,746** |
| Uber Bases | **5** |
| Highest Monthly Volume | **September** |
| September Trips | **1,004,099** |
| Peak Recorded Hour | **5 PM** |
| Trips at Peak Hour | **330,024** |
| Busiest Day | **Thursday** |
| Thursday Trips | **741,372** |

### Main Observations

- Recorded trip volume increased from April to September.
- September recorded the highest monthly trip volume.
- 5 PM recorded the highest hourly trip activity.
- Thursday recorded the highest daily trip volume.
- Pickup activity was concentrated in specific geographic areas.
- Trip activity varied considerably across Uber bases.

---

## 💼 Business Recommendations

Based on the analysis:

- Use historical hourly demand patterns to support driver availability planning.
- Consider daily and monthly demand patterns when planning operational resources.
- Use geographic demand concentration to support local driver allocation.
- Monitor differences in recorded activity across Uber bases.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📁 Project Structure

```text
Uber-NYC-Data-Analysis/
│
├── Uber_NYC_Data_Analysis.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── visuals/
    ├── monthly_trips.png
    ├── hourly_trips.png
    ├── day_of_week_trips.png
    ├── day_hour_heatmap.png
    ├── base_analysis.png
    ├── pickup_locations.png
    └── pickup_density.png