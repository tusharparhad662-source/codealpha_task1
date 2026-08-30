# codealpha_task1
# 🚆 Indian Railway Train Dataset – Exploratory Data Analysis

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an
Indian Railway Train Dataset. The objective is to understand the structure,
quality, and characteristics of the dataset before performing further analysis
and visualization.

The dataset contains detailed information about trains, their routes,
stations, arrival and departure timings, sequence numbers, distances, and
source and destination stations.

## 🎯 Objectives

The main objectives of this EDA are:

- Understand the structure and characteristics of the dataset.
- Analyze different variables and their data types.
- Identify missing values and duplicate records.
- Explore train and station frequency patterns.
- Analyze route distances and station sequences.
- Detect invalid, inconsistent, or anomalous records.
- Prepare the dataset for further data visualization.

## 📊 Dataset Summary

- **Total Records:** 186,124
- **Total Columns:** 12
- **Unique Trains:** ~11,115
- **Unique Stations:** ~8,151
- **Duplicate Records:** 0
- **Columns with Missing Values:** 7

## 🔍 Key Findings

The exploratory analysis revealed that the dataset contains a large number
of train-station records covering thousands of trains and railway stations.

Several columns contain missing values, particularly arrival time, departure
time, distance, source station, and destination station information.

The analysis also identified a small number of malformed or inconsistent
records, indicating potential data quality issues that should be addressed
before conducting further analysis.

Train route distances vary considerably, with some routes covering distances
of more than 4,000 km. The dataset also shows that certain railway stations
and trains occur much more frequently than others.

## ⚠️ Data Quality Observations

- Missing values were found in 7 columns.
- No completely duplicated rows were identified.
- Some numerical fields are stored as text/object data types.
- A few records contain invalid or misaligned values.
- Delay analysis cannot be performed because the dataset does not contain
  both scheduled and actual arrival/departure times.



