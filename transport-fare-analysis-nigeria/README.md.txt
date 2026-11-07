# Transport Fare Analysis in Nigeria 🇳🇬

## Project Overview

This project explores transport fare patterns across different states, routes, and transport types in Nigeria using Microsoft Power BI and Microsoft Excel.

The analysis focuses on understanding variations in transportation costs, comparing average fares across locations and transport categories, and presenting the data through interactive visualisations.

## Project Objectives

The main objectives of this project are to:

- Analyse average transport fares across Nigerian states.
- Compare average fares across different transport types.
- Examine the distribution of routes by transport type.
- Identify routes with relatively high average fares.
- Explore how transportation costs vary across different routes.
- Present insights through an interactive Power BI report.

## Dataset Description

The dataset used for this project contains:

- **52,500 records**
- **8 columns**
- **36 states** after standardising state names
- **11 transport types** after standardising transport-type entries
- **226 distinct routes** after standardising route entries

### Dataset Fields

| Column | Description |
|---|---|
| State | Nigerian state associated with the transport record |
| Transport Type | Category of transportation |
| Route | Travel route recorded |
| Distance (KM) | Distance covered in kilometres |
| Fare (NGN) | Recorded transport fare in Nigerian Naira |
| Notes | Additional information |
| Entered By | Record entry information |
| Random Text | Additional text field |

## Tools and Technologies

- **Microsoft Excel:** Dataset inspection and preparation.
- **Microsoft Power BI:** Data modelling, analysis, and interactive visualisation.

## Analysis and Visualisations

The Power BI report includes the following analytical visuals:

1. Average Fare by Route
2. Average Fare by Transport Type
3. Count of Routes by Transport Type
4. Average Fare by State

The report contains two main pages:

- **Chart:** Presents the individual analytical visualisations.
- **Dashboard and Wireframe:** Provides the dashboard presentation of the analysis.

## Project Structure

```text
transport-fare-analysis-nigeria/
│
├── README.md.txt
│
├── dataset/
│   └── DATASET.xlsx.xlsx
│
├── power-bi/
│   └── Transport_Fare_Analysis.pbix.pbix
│
├── screenshots/
│   ├── 01_Power_BI_Dashboard.png.png
│   ├── 02_Charts_and_Analysis.png
│   ├── 03_Average_Fare_by_Route.png.png
│   ├── 04_Average_Fare_by_Transport_Type.png.png
│   ├── 05_Route_Count_by_Transport_Type.png.png
│   └── 06_Average_Fare_by_State.png.png
│
└── documentation/
    └── Project_Overview.md.txt
```

## Data Preparation

The dataset was inspected for missing values, inconsistent text formatting, duplicate records, and issues affecting numerical analysis.

Preparation considerations included standardising state names, transport-type entries, and route descriptions, as well as reviewing fare values to support meaningful numerical analysis.

## Project Files

- **Power BI Report:** `power-bi/Transport_Fare_Analysis.pbix.pbix`
- **Dataset:** `dataset/DATASET.xlsx.xlsx`
- **Project Documentation:** `documentation/Project_Overview.md.txt`
- **Dashboard and Chart Screenshots:** `screenshots/`

## Conclusion

This project demonstrates the application of data analytics and business intelligence tools to explore transportation costs in Nigeria. It highlights how data preparation, analysis, and visualisation can help transform raw transportation records into information that is easier to explore and understand.

---

**Project Category:** Data Analytics | Business Intelligence

**Primary Tool:** Microsoft Power BI

**Supporting Tool:** Microsoft Excel
