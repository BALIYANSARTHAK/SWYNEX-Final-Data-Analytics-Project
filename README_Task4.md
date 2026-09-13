# Task 4 – Final Data Analytics Project
**SWYNEX Technologies · Data Analyst Internship · SARTHAK BALIYAN**

## Overview

This repository is the final capstone case study for the SWYNEX Data
Analyst Internship, combining the work from Tasks 1–3 into a single,
end-to-end analytics narrative: **problem statement → dataset → cleaning
→ analysis → dashboard → business insights.**

📄 **Full case study document:**  [`SWYNEX_Task4_Final_Case_Study.pdf`](https://drive.google.com/file/d/1pc1ndjxtf_hrt-cNk8lx_rnjWf3Wz1Y5/view?usp=drive_link)

## Problem Statement

Superstore's overall profit margin (10.2%) looks healthy at a glance, but
this project set out to find out what a top-line view hides — specifically,
whether certain products, categories, or order types are quietly losing
money, and what's driving it.

## Dataset

Superstore Sales (Canada) — 8,399 orders, January 2009 to December 2012.
[Dataset Link](https://drive.google.com/file/d/1jV4wLWkUCAN7b3OopbOO4xJ8GJC-ryjy/view?usp=drive_link)

## Project Structure

| Stage | Task | What was done | Link |
|---|---|---|---|
| 1 | Data Cleaning | Fixed data types, a misspelled province, missing values | [Task 1 repo](https://github.com/BALIYANSARTHAK/SWYNEX-Data-Cleaning-Preparation.git) |
| 2 | Exploratory Analysis | Found 50.8% of orders are unprofitable; Furniture's 2.3% margin problem | [Task 2 repo](https://github.com/BALIYANSARTHAK/SWYNEX-Exploratory-Data-Analysis.git) |
| 3 | Interactive Dashboard | Power BI dashboard with KPIs, charts, and filters | [Task 3 repo](https://github.com/BALIYANSARTHAK/SWYNEX-Interactive-Dashboard.git) |
| 4 | Final Case Study | This document — the complete narrative | [Task 4 repo](https://github.com/BALIYANSARTHAK/SWYNEX-Final-Data-Analytics-Project.git) |


## Key Findings Summary

1. **Furniture** generates $5.18M in sales (nearly matching Technology's
   $5.98M) but earns only a **2.3% profit margin** vs. 14.8% for
   Technology and 13.8% for Office Supplies.
2. **50.8% of all 8,399 orders are individually unprofitable**, despite
   the business being profitable overall — a sign of systemic pricing
   issues, not isolated bad orders.
3. **Tables (-$99,063) and Bookcases (-$33,582)** drive the majority of
   Furniture's losses.
4. **Discounting is not the cause** — correlation between discount and
   profit is only -0.037.
5. **Sales declined ~12%** from 2009 to 2011 before a modest 2012
   recovery.

## Tools Used

Python (pandas, matplotlib) for cleaning and analysis · Power BI Desktop
for the interactive dashboard · Word/PDF for this final case study
document.

## How to view

- Read the **PDF** for a quick view without any software
- Open the **.docx** to see/edit the full formatted report
- See the individual Task 1–3 repos linked above for all underlying code,
  the cleaned dataset, EDA charts, and the live `.pbix` dashboard file
