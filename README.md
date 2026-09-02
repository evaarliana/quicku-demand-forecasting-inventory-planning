# Demand Forecasting & Inventory Planning

## Project Overview

QuickU is a Q-Commerce platform focused on acquiring quality users while maintaining efficient inventory planning. As demand fluctuates across time, categories, and hubs, inaccurate inventory planning can lead to stock shortages or excess and expired stock.

This project analyzes historical demand patterns and develops a demand forecasting approach to support inventory planning and resource allocation across hubs and product categories.

**Project Duration:** August 2026 - August 2026

---

## Business Problem

How can QuickU forecast future demand and translate the forecast into inventory planning priorities to reduce stockout and overstock risks?

---

## Objectives

- Analyze historical demand patterns across time, hubs, and product categories.
- Develop and evaluate demand forecasting models.
- Select the most appropriate forecasting approach based on model performance.
- Translate forecast results into inventory planning priorities.
- Provide actionable recommendations for demand and inventory management.

---

## Analytical Approach

The analysis follows an end-to-end workflow:

**Data Preparation → Exploratory Data Analysis → Demand Forecasting → Model Evaluation → Inventory Risk Analysis → Business Recommendations**

### 1. Data Preparation

- Prepared and validated historical transaction data.
- Aggregated demand by relevant time periods, hubs, and product categories.
- Checked data consistency before forecasting.

### 2. Exploratory Data Analysis

- Analyzed historical demand trends.
- Identified demand patterns across weeks, hubs, and categories.
- Evaluated demand variability to identify potential inventory risks.

### 3. Demand Forecasting

- Developed multiple forecasting approaches.
- Compared model performance using forecasting error metrics.
- Selected the **4-Week Moving Average** as the preferred forecasting approach based on model evaluation results.

### 4. Inventory Planning

- Generated demand forecasts for August 2022.
- Compared forecasted demand across hubs and categories.
- Evaluated demand share and volatility to identify inventory priorities.

---

## Key Findings

### 📈 Demand Forecast

The selected forecasting approach estimated approximately **442.9K units** of total demand for August 2022.

### 📅 Weekly Demand

Demand was expected to peak in **Week 4**, reaching approximately **120.1K units**.

### 🛒 Category Performance

**H. Sayur & Buah** recorded the highest August forecast at approximately **136.8K units**, indicating the strongest expected demand among categories.

### 📍 Hub Performance

**Hub E** recorded the highest August forecast at approximately **100.1K units**, making it a key location for inventory planning.

### ⚠️ Demand vs. Inventory Risk

High demand does not necessarily indicate the highest inventory risk. Categories with lower demand shares can still require attention when demand volatility is high.

---

## Business Recommendations

- Prioritize inventory allocation for high-demand categories and hubs.
- Maintain higher stock readiness ahead of peak-demand periods.
- Monitor highly volatile categories even when their overall demand share is relatively small.
- Use demand forecasts as a planning input for replenishment and inventory allocation.
- Continuously update forecasts as new demand data becomes available.

---

## Dashboard

The interactive dashboard provides an overview of:

- August demand forecast
- Weekly demand forecast
- Historical demand trends
- Forecast by product category
- Forecast by hub
- Hub × category demand distribution

![QuickU Demand Forecasting Dashboard](./dashboard/Demand%20Forecasting%20%26%20Inventory%20Planning.jpg)

---

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Power BI

---

## Project Files

| File | Description |
|---|---|
| `QuickU_Stock_Planning_Forecasting.ipynb` | Data analysis and demand forecasting workflow |
| `Dashboard.pdf` | Exported Power BI dashboard |
| `Dashboard.jpg` | Dashboard preview |
| `Presentation.pdf` | Project presentation and business insights |

---

## Disclaimer

This project was developed for educational and portfolio purposes. QuickU is a case-study business context, and the analysis should not be interpreted as actual business performance or operational recommendations for a real company.
