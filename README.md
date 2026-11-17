# Smoking & Health Analysis Dashboard

## Project Overview

The **Smoking & Health Analysis Dashboard** is an interactive data analytics project developed using Microsoft Power BI. It focuses on analyzing smoking patterns, patient demographics, and their association with different health conditions.

The dashboard transforms patient-related data into meaningful visual insights, helping explore smoking behavior, health conditions, organ-related diagnoses, and potential health risks.

## Objectives

- Analyze smoking patterns across different patient demographics.
- Understand the distribution of current smokers.
- Explore the relationship between smoking exposure and diagnosed health conditions.
- Examine organ-wise health condition distribution.
- Analyze cholesterol levels across blood pressure risk categories.
- Identify patterns based on age group, gender, and region.

## Dashboard Pages

### 1. Smoking Overview

Provides an overview of patient demographics and smoking behavior.

Key components:
- Total Patients
- Current Smokers
- Patients with Recorded Conditions
- Patients with Recorded Organ Conditions
- Smoking Status Distribution
- Average Cigarettes Per Day
- Current Smokers by Age Group

**Interactive Filters:**
- Region
- Age Group
- Gender
- Smoking Status

### 2. Health Risk Analysis

Focuses on exploring health conditions and their relationship with smoking exposure.

Key visualizations:
- Average Cholesterol by BP Risk Category
- Organ-wise Health Condition Distribution
- Health Conditions by Smoking Exposure Level

## Tools & Technologies

- **Microsoft Power BI** – Dashboard development and data visualization
- **Power Query** – Data preparation and transformation
- **DAX (Data Analysis Expressions)** – Calculated measures and analytical calculations

## Key DAX Measures

The project includes measures such as:

- Total Patients – Calculates the distinct number of patients.
- Current Smokers – Counts patients categorized as current smokers.
- Patients with Recorded Condition – Counts patients with diagnosed health conditions.
- Patients with Recorded Organ – Counts patients with recorded organ conditions.

## Dataset Attributes

The data model includes the following attributes:

- Patient_ID
- Age
- Gender
- Region
- Diagnosis_Date
- Smoking_Status
- Cigarettes_Per_Day
- Years_Smoking
- Diagnosed_Organ
- Health_Condition
- Total_Cholesterol_mg_dL
- Systolic_BP_mmHg
- Diastolic_BP_mmHg
- BMI
- Resting_Heart_Rate_bpm

Additional calculated fields include Age Group, BP Risk Category, Estimated Smoking Exposure, and Exposure Level.

## Project File

The repository contains the Power BI Template (`.pbit`) file.

To explore the dashboard:
1. Download the `.pbit` file.
2. Open it using Microsoft Power BI Desktop.
3. Provide the required data source if prompted.
4. Load the data and explore the interactive dashboard.

## Learning Outcomes

Through this project, I explored:

- Data modeling and transformation in Power BI.
- Creating calculated measures using DAX.
- Designing interactive dashboards.
- Working with patient demographic and health-related attributes.
- Building visualizations to communicate analytical findings.

## Disclaimer

This project is intended for educational and data analytics purposes only. The visualizations should not be interpreted as medical advice or proof of causation between smoking and specific health conditions.

---

**Developed as a Data Analytics Project using Microsoft Power BI.**
