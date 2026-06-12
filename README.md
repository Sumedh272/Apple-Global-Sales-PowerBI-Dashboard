# Apple Inc. Global Performance & Operations Dashboard (2020 - 2024)

## Project Overview
This repository contains an end-to-end Business Intelligence solution built in Power BI Desktop to track and analyze Apple Inc.'s global sales data, product-level margins, and operational workflows. 

The dashboard transitions through three analytical layers—Sales Overview, Products Overview, and Revenue Details—to eliminate enterprise informational silos and enable data-driven executive decision-making.

---

## Key Visuals & Architecture

### 1. Sales Overview (Macro Health Layer)
Provides an immediate bottom-line pulse check featuring customized, low-contrast UI containers and application-like bookmark button groups for smartphone, laptop, and accessory slicing.
![Sales Overview]

### 2. Products Overview (Granular Distribution Layer)
Examines product performance through granular accounting matrices, cross-analyzes unit volumes against value, and provides spatial intelligence via geographical sales mapping.
![Products Overview]

### 3. Revenue Details (Operational Diagnostic Layer)
Tracks financial momentum using advanced metrics (YoY Growth % and Revenue LY), isolates retail outlet performance, and maps product quality risks using visual claim treemaps.
![Revenue Details]

---

## Core Business Problems Solved
* **The 2024 Performance Turn:** Visualizes and isolates the root causes behind a noticeable macroeconomic downward shift in revenue moving from 2023 into 2024.
* **Operational Risk Warning:** Flags service pipeline backlogs by surfacing an executive metric alert for 8K pending warranty claims.
* **User Experience Optimization:** Replaces clunky default filtering with native bookmark and page navigation button actions for clean, interactive user paths.

---

## Tools & Tech Stack Used
* **Power BI Desktop:** Data modeling, UI/UX container design, and canvas architecture.
* **DAX (Data Analysis Expressions):** Time-intelligence modeling (YoY Growth %, Revenue LY, Revenue QoQ, Avg Order Value, Claim Resolution Rate %).
* **Excel / CSV:** Relational database storage for core schema tables (Sales, Products, Stores, Warranty, Category, Date).

---

## How to View the Dashboard
1. Download the `Apple_Global_Sales_Dashboard.pbix` file from this repository.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open the file to interact with the bookmarks, slicers, and navigation bars natively. (Remember to hold `Ctrl + Click` to trigger button actions in Desktop mode!)
