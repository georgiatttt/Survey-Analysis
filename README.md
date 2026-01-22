# City Harvest Capacity Analysis

This project analyzes operational and demographic survey data from food pantries to better understand capacity constraints, resource gaps, and service coverage.

The goal is to transform raw survey data into structured metrics and scores that support data-driven decision making.

---

## Overview

Using cleaned and synthesized survey data, this project explores relationships between pantry capacity, demand, staffing, and neighborhood characteristics. The analysis emphasizes interpretable feature engineering and scoring logic rather than black-box prediction.

Work is organized to clearly separate exploration, scoring methodology, and reusable code.

---

## Key Components

- Data cleaning and preprocessing of partner survey responses  
- Feature engineering and capacity scoring methodology  
- Exploratory analysis of operational and demographic patterns  
- Modular Python code to support reuse and iteration  

---

## Project Structure

```text
CH/
├── notebooks/          # Exploratory analysis and scoring notebooks
├── src/                # Reusable data processing and scoring logic
├── data/               # Raw and processed datasets
├── requirements.txt    # Python dependencies
└── README.md

