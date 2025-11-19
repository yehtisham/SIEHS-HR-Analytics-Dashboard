HR Data Analysis and Workforce Performance Insights (SIEHS)

Author: Muhammad Yahya

Confidentiality Notice:
This repository contains no sensitive company information. All data used is authorized, sanitized, and safe 
Overview

This project processes and analyzes attendance and HR operations data for Sindh Integrated Emergency & Health Services (SIEHS). The goal was to clean fragmented Excel files, standardize time and attendance records, and build a unified dataset for performance monitoring through a Power BI dashboard.

This repository includes:

Final Analysis Report (PDF)

Clean R code for data processing

Master dataset creation pipeline

Dashboard image (PBIX not included)

Objectives

Consolidate five HR data sources

Correct and standardize date/time formats

Remove invalid or inconsistent entries

Compute key workforce metrics:

Attendance & absences

Working hours

Late arrivals

Approved / unapproved leaves

Invalid entries

Build a single analytics-ready master dataset

Generate insights for HR and operations teams

Method Summary

Data Cleaning

Column normalization

Date/time conversion

Removal of duplicates and invalid rows

Reconstruction of Time-In/Time-Out

Attendance Processing

Reshaped daily attendance using pivot_longer()

Computed working hours, absences, holidays, and invalid timestamps

KPI Engineering

Total assigned duties

Attended vs. absent days

Working hours

Leave categories

Invalid entry counts

Schedule status

Master Dataset
Merged all sources using Emp Index, producing a unified employee-level dataset used for dashboarding.

Dashboard Insights

On-time arrival trends

Department-level punctuality

Late arrival patterns

Shift compliance

Employee-level summaries

A static dashboard preview is included.

Contact

Muhammad Yahya
Email: yahyaehtisham2004@gmail.com
