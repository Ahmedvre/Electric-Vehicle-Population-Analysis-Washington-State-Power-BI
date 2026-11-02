# Electric Vehicle Population Analysis – Washington State

## 📌 Project Overview

This project presents an interactive analysis of electric vehicle registration data in Washington State, USA, using **Microsoft Power BI**.

The main objective is to explore electric vehicle population patterns, identify leading manufacturers, analyze geographical distribution, and extract meaningful insights through interactive dashboards.

Data preparation and cleaning were performed using **Power Query**, followed by data visualization and analysis in Power BI.

## 🛠️ Tools & Technologies

- **Microsoft Power BI:** Dashboard development and data visualization.
- **Power Query:** Data cleaning, transformation, and preparation.
- **DAX:** Creating measures and analytical calculations.

## 📂 Dataset

**Dataset:** Electric Vehicle Population Data

**Source:** Washington State Department of Licensing (DOL).

[Official Dataset – Data.WA.gov](https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2)

The dataset contains information about Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered in Washington State.

Key attributes include:

- Vehicle Make and Model
- Model Year
- Electric Vehicle Type
- County and City
- Electric Range
- CAFV Eligibility
- Vehicle Location (Longitude and Latitude)

## 🔄 Data Preparation & Cleaning – Power Query

Power Query was used to prepare and clean the source data before building the dashboard.

The preparation process focused on:

- Reviewing the dataset structure and data quality.
- Cleaning and transforming data.
- Checking and assigning appropriate data types.
- Preparing fields for geographical and analytical visualizations.
- Handling missing or unknown values appropriately.
- Ensuring the data was suitable for reporting and analysis.

## 📊 Power BI Dashboard

The report consists of two interactive pages.

### 1. Executive Overview

Provides a high-level overview of the electric vehicle population in Washington State.

**Key Performance Indicators (KPIs):**
- Total Electric Vehicles
- Battery Electric Vehicles (BEVs)
- Plug-in Hybrid Electric Vehicles (PHEVs)
- Total Manufacturers
- Total Vehicle Models

**Visualizations:**
- Vehicle Population by Model Year.
- Top 10 Electric Vehicle Manufacturers.
- Top 10 Counties by Vehicle Population.
- Top 10 Cities by Vehicle Population.
- Electric Vehicle Type Distribution.
- CAFV Eligibility Distribution.

![Executive Overview](Dashboard-Images/Executive-Overview.png)

### 2. Geographic Analysis

Focuses on exploring the geographical distribution of electric vehicles across Washington State.

**Visualizations:**
- Geographic Distribution using Bubble Map.
- Vehicle Population by City.
- Manufacturer Distribution using Treemap.
- Geographic concentration across different locations.

**Interactive Filters:**
- Manufacturer
- County
- City
- Model Year
- Electric Range
- CAFV Eligibility

![Geographic Analysis](Dashboard-Images/Geographic-Analysis.png)

## 🔍 Key Insights

Based on the dashboard analysis:

- **Vehicle Types:** BEVs represent approximately 80.5% of the total records, while PHEVs account for approximately 19.5%.
- **Leading Manufacturer:** Tesla leads the manufacturers with approximately 122K vehicle records.
- **County Analysis:** King County has the highest vehicle population, with approximately 143K records.
- **City Analysis:** Seattle ranks first among cities, with approximately 45K vehicle records.
- **CAFV Eligibility:** Approximately 65.6% of records have an Unknown eligibility status, highlighting the importance of data quality and proper interpretation.

*Note: Figures represent the dashboard snapshot and may vary depending on the dataset version and applied filters.*

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and transformation using Power Query.
- Preparing datasets for analytical reporting.
- Creating DAX measures and calculations.
- Designing interactive Power BI dashboards.
- Using geographical visualizations to explore location-based patterns.
- Applying visual storytelling to communicate analytical findings.
- Translating raw data into meaningful insights.

---

**This project reflects my practical application of Power BI in transforming raw data into interactive visualizations and actionable insights as part of my journey in Data Analytics.**
