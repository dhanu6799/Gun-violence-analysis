# Gun Violence Analysis (2013 - 2018)

## Overview
This repository contains a comprehensive analysis of gun violence incidents in the United States from 2013 to 2018. The project leverages advanced data processing and machine learning tools, including PySpark and Kafka, to uncover trends, assess incident severity, and identify high-risk zones. The goal is to provide valuable insights for policymakers, law enforcement, and stakeholders to inform targeted interventions and improve public safety.

## Table of Contents
- [Project Objectives](#project-objectives)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

## Project Objectives
- Analyze the frequency and severity of gun violence incidents across different states and time periods.
- Identify high-risk and low-risk zones based on historical data.
- Develop a predictive model for classifying the severity of future incidents.

## Data Description
- **Source**: Kaggle dataset on U.S. gun violence (239,678 records, 29 variables). [Access the dataset here](https://www.kaggle.com/datasets/jameslko/gun-violence-data).
- **Variables**: Includes incident ID, date, location, number of fatalities/injuries, demographics, and types of firearms involved.

## Methodology
### 1. Exploratory Data Analysis (EDA)
- Utilized statistical summaries and visualizations to understand data distribution and spot anomalies.

### 2. Data Preprocessing
- Employed string splitting with regex and PySpark’s `VectorAssembler` for feature aggregation.

### 3. Clustering
- Implemented K-means clustering to identify high-risk and low-risk zones based on incident data.

### 4. Graph Analysis
- Used graph frames to model relationships and visualize incident trends geographically and temporally.

### 5. Streaming Analysis
- Demonstrated real-time data processing using Kafka and PySpark streaming capabilities.

### 6. Classification
- Applied a Random Forest classifier to categorize incidents into low, medium, and high severity, achieving an accuracy of 77.89%.

## Key Findings
- **High-Risk Zones**: Major cities like Chicago, Baltimore, and Washington, D.C., were identified as high-risk areas.
- **Temporal Trends**: Certain years and months showed spikes in incidents, highlighting seasonal trends.
- **Demographic Insights**: Male individuals were more frequently involved in gun incidents across all severity levels.
- **Geographical Focus**: California had the highest number of incidents and fatalities, indicating the need for focused policy intervention.

## Technologies Used
- **PySpark**: For data processing, EDA, clustering, and classification.
- **Kafka**: For streaming analysis and real-time data simulation.
- **Machine Learning**: Implemented Random Forest classifier.
- **Graph Frames**: For relationship modeling and trend visualization.
- **Python Libraries**: NumPy, Pandas, Matplotlib.

## Conclusions
This project highlights the complex nature of gun violence in the U.S. and provides data-driven insights for policymakers. By leveraging machine learning and data streaming technologies, we demonstrated a comprehensive approach to understanding and mitigating gun violence through informed decision-making and targeted interventions.

---
Explore the notebooks, data, and visualizations included in this repository to gain deeper insights into the analysis.
