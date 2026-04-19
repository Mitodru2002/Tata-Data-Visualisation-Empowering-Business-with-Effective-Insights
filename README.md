# Tata-Data-Visualisation-Empowering-Business-with-Effective-Insights
Strategic data visualization project for Tata Group, leveraging Python for data engineering and Power BI to identify global expansion opportunities, seasonal revenue trends, and customer high-value segments.


# 📊 Tata Data Visualisation: Empowering Business with Effective Insights

This repository contains a strategic data analytics project developed for **Tata Group**. The goal was to transform raw transactional data into actionable business intelligence using **Python** for data engineering and **Power BI** for executive storytelling.

## 🖼️ Dashboard Preview

> *Above: A comprehensive view of the Tata Retail Executive Dashboard.*

-----

## 🚀 Project Overview

The leadership team at Tata required a deep dive into 2011 fiscal performance to guide their global expansion strategy. This project addresses four critical business questions:

1.  **Revenue Trends:** Identifying seasonal peaks to optimize supply chain.
2.  **Market Prioritization:** Highlighting top international markets (excluding the UK).
3.  **Customer Intelligence:** Profiling the top 10 high-value customers to assess revenue risk.
4.  **Expansion Mapping:** Visualizing global demand "hotspots" for new distribution hubs.

-----

## 🛠️ Tech Stack

  * **Data Engineering:** Python (Pandas) for rigorous data scrubbing.
  * **Business Intelligence:** Power BI Desktop for interactive visualization.
  * **Analysis Logic:** Statistical filtering of outliers and accounting errors.

-----

## 🧹 The "Gold Standard" Cleanup

To ensure the CEO and CMO received error-free insights, I implemented a Python-based cleaning pipeline:

  * **Return Filtering:** Removed over 8,000 records with negative quantities.
  * **Price Correction:** Filtered out unit prices below 0.
  * **Feature Engineering:** Calculated `Total_Revenue` ($Quantity \times UnitPrice$) and synchronized date formats for time-series accuracy.

-----

## 📈 Visual Analysis

### 1\. Revenue Seasonality

  * **Insight:** Significant growth begins in September, peaking in **November at $1.5M**.

### 2\. Global Expansion Hotspots

  * **Insight:** Outside the UK, the **Netherlands, Germany, and France** show the highest demand. I recommend a regional distribution hub in Central Europe to reduce lead times.

### 3\. Customer Concentration

  * **Insight:** The narrow gap between top spenders indicates a healthy, diversified customer base with low dependency risk.

-----

## 📂 Repository Structure

  * `data/`: Cleaned dataset used for the Power BI report.
  * `notebooks/`: Python script for data cleaning and EDA.
  * `visuals/`: Includes the `.pbix` file and high-resolution screenshots.

**Author:** Mitodru Mridha 
**Project:** Tata Data Visualisation Job Simulation  
**Date:** April 2026

-----

