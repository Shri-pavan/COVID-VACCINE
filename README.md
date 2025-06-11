# India COVID-19 Vaccination Drive: Analysis & Dashboard

## 🚀 Project Overview

This project provides a complete analysis of India's COVID-19 vaccination campaign, from initial data processing in Microsoft Excel to a final, interactive dashboard. Using a state-wise dataset, it explores the distribution of vaccine doses and the progress of vaccination coverage across the country. The goal is to derive insights into the effectiveness and reach of the national vaccination drive through a structured data workflow.

## 📊 The Dataset

The primary data source is a snapshot of vaccination status for 37 states and union territories in India. The key columns include:

* **State_or_UT:** The name of the region.
* **Population:** The total population of the region.
* **Dose_1 & Dose_2:** The total number of first and second doses administered.
* **Cumulative_Dose:** The total of all doses administered.
* **Percentage_Fully_Vaccinated:** The percentage of the population fully vaccinated.

## ⚙️ Project Workflow

This project follows a two-part workflow, starting in Excel and extending to Tableau for advanced visualization:

1.  **Data Processing & Dashboarding in Excel:** The raw data is first cleaned, aggregated using PivotTables, and visualized in a self-contained Excel dashboard.
2.  **Interactive Visualization in Tableau:** The processed data is then used to build a more dynamic and shareable interactive dashboard in Tableau.

---

### Part 1: Analysis & Dashboard in Microsoft Excel

The Excel workbook is a complete BI tool, structured with separate sheets for raw data (`Covid`), processed data (`INPUT`), and presentation (`Dashboards`).

The Excel dashboard provides a comprehensive overview with:
* **Key Performance Indicators (KPIs):** Displays high-level national totals for doses administered.
* **State-wise Performance Views:** Ranks states based on both absolute dose counts and vaccination percentages.
* **Dose Gap Analysis:** Compares the administration of Dose 1 versus Dose 2 for each state.
* **Interactive Controls:** Features Slicers to filter the data and dynamically explore the performance of individual states.

---

### Part 2: Interactive Tableau Dashboard

For advanced and shareable visualizations, the data is presented in a Tableau dashboard titled **"India's COVID-19 Vaccination Drive Tracker."**

The dashboard features several key analytical views:

* #### **Vaccination Coverage Percentage**
    A geographical overview of India where each state is color-coded to represent its progress toward full vaccination.

* #### **Vaccination Progress by State**
    A comprehensive ranking of all states and union territories based on the total number of cumulative vaccine doses administered.

* #### **Fully Vaccinated %**
    This analysis ranks all states according to the percentage of their population that has been fully vaccinated, highlighting regional efficiency.

* #### **Dose Comparison**
    A direct comparison for each state between the total first doses and second doses administered, illustrating the "coverage gap."

* #### **Population vs. Vaccination**
    An exploration of the relationship between a state's population size and its total vaccination effort.

## 📋 How to Use This Repository

1.  **For Excel Analysis:**
    * Open the `Covid.xlsx` file.
    * Navigate to the **"Dashboards"** sheet to interact with the visuals and slicers.
    * Explore the **"INPUT"** and **"Covid"** sheets to understand the underlying data and PivotTable structure.
2.  **For Tableau Dashboard:**
    * Download and install the free [Tableau Public](https://public.tableau.com/en-us/s/download) application.
    * Open the accompanying `.twbx` file to view and interact with the complete dashboard.
