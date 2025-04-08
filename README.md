# 🏡 AirBnB Data Analysis (Tableau + Excel)

This repository contains a Tableau-based exploratory analysis of an AirBnB dataset. Using a structured Excel file as the data source, the dashboard presents visual summaries of pricing, availability, capacity, and revenue trends across different property types and locations.

<p align="center">
  <img src="AirBnB Dashboard.png" alt="AirBnB Dashboard" width="90%">
</p>

---

## 📌 Project Description

The goal of this project was to identify patterns in AirBnB listings using visual analytics. The analysis focuses on:

- Variation in **average price** based on **bedroom count** and **zip code**
- Distribution of properties by **bedrooms** and **guest capacity**
- Estimation of **total revenue over time** (based on listings and average prices)

All visuals and insights were built using **Tableau Desktop**, powered by a cleaned Excel dataset.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `AirBnB Data.xlsx` | Dataset used for visualization (uploaded using Git LFS) |
| `AirBnB Data Analysis.twbx` | Tableau packaged workbook containing the dashboard |
| `AirBnB Dashboard.png` | Static image of the final dashboard layout |

> ⚠️ Note: `AirBnB Data.xlsx` exceeds GitHub’s file size limit and is tracked using **Git LFS**.  
> To access the file, make sure to install Git LFS and run `git lfs pull` after cloning.

---

## 📊 Dashboard Summary

The dashboard is divided into the following sections:

### 1. **Average Price by Bedrooms**
- Shows how average listing prices increase with the number of bedrooms
- Listings with 6 bedrooms average over \$580

### 2. **Average Price by Zipcode**
- Bar chart ranking zip codes by average price
- Highest-priced zip code: 98134 (\$206.6)

### 3. **Property Count by Bedrooms**
- Table summarizing how many listings exist for each bedroom count
- Majority of properties have 1 bedroom

### 4. **Accommodates per Property**
- Bar chart showing how many guests listings can accommodate
- Most listings accommodate 2–4 people

### 5. **Total Revenue of the Year (2016)**
- Line chart showing cumulative revenue across 2016 (based on calculated estimates)
- Revenue growth appears stable with minor fluctuations mid-year

---

## 🛠 Tools Used

- **Tableau Desktop (.twbx)** – for dashboard design and visual analytics
- **Microsoft Excel (.xlsx)** – for data preparation and structure
- **Git + Git LFS** – for version control and storing large files

---

## 👤 Contributor

- [Azim Nahin](https://github.com/AzimNahin)

---

## 📷 Dashboard Preview

![AirBnB Dashboard Preview](AirBnB%20Dashboard.png)
