# Electric Vehicle Population Dataset Analysis

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Notebooks and Files](#notebooks-and-files)
5. [Key Insights](#key-insights)
6. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Running the Project](#running-the-project)
7. [Project Report](#project-report)
8. [Conclusion](#conclusion)

---
## Introduction

This project focuses on analyzing the population and distribution of electric vehicles (EVs) using a comprehensive dataset. By performing data cleaning, exploratory data analysis (EDA), and feature engineering, the project uncovers trends and insights into EV adoption across various regions.

---
## Features

- **Data Cleaning**:
  - Handled missing values and standardized data types for effective analysis.
  - Converted fields such as `Postal Code` and `Legislative District` to appropriate formats.

- **Exploratory Data Analysis (EDA)**:
  - Examined trends in EV adoption by `Make`, `Model Year`, `County`, and `Electric Vehicle Type`.
  - Explored the relationship between `Electric Range`, `Base MSRP`, and EV eligibility for Clean Alternative Fuel Vehicle (CAFV) programs.

- **Visualization**:
  - Created visualizations to identify geographic and demographic patterns in EV adoption.
  - Mapped vehicle locations to highlight distribution across regions.

- **Feature Engineering**:
  - Generated additional insights by engineering features like eligibility for CAFV programs and battery range categories.

---

## Dataset

The dataset used in this project contains the following columns:
- **VIN (1-10)**: Vehicle Identification Number (partial).
- **County, City, State, Postal Code**: Geographic location of the vehicle.
- **Model Year, Make, Model**: Details of the vehicle's manufacturer and specifications.
- **Electric Vehicle Type**: Type of EV (e.g., Battery Electric Vehicle (BEV), Plug-in Hybrid Electric Vehicle (PHEV)).
- **Electric Range**: Distance the vehicle can travel on electric power.
- **Base MSRP**: Manufacturer's Suggested Retail Price.
- **Clean Alternative Fuel Vehicle (CAFV) Eligibility**: Eligibility for clean fuel programs.
- **Legislative District**: Legislative district of the vehicle's registered location.
- **Vehicle Location**: Geographic coordinates of the vehicle.
- **Electric Utility**: Utility company serving the vehicle's location.
- **2020 Census Tract**: Census tract of the vehicle's location.

---

## Notebooks and Files

- **`Electric_Vehicle_Population.ipynb`**:
  - Main analysis notebook that includes data cleaning, exploratory data analysis, and feature engineering.
  
- **`Electric_Vehicle_Population_Data.csv`**:
  - Raw dataset containing information about electric vehicles.

- **`paper.pdf`**:
  - Project documentation that includes detailed insights, methodologies, and findings.

---

## Key Insights

- **EV Adoption Trends**:
  - Tesla dominates the EV market with high adoption rates across various counties.
  - Battery Electric Vehicles (BEVs) are more prevalent than Plug-in Hybrid Electric Vehicles (PHEVs).

- **Geographic Analysis**:
  - King County has the highest concentration of EVs.
  - Geographic distribution highlights the influence of urban centers on EV adoption.

- **CAFV Eligibility**:
  - Vehicles with higher electric range are more likely to be eligible for clean fuel programs.
  - Insightful patterns were observed between vehicle price and eligibility.

---

## Getting Started

### Prerequisites

- Install Python 3.x and Jupyter Notebook.
- Install required Python libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn

### Running the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/Lanamahd/Electric_Vehicle_Population_Dataset_Analysis.git
    cd Electric_Vehicle_Population_Dataset_Analysis


2. Open the Jupyter Notebook:
   jupyter notebook Electric_Vehicle_Population.ipynb
   
3. Follow the cells to execute the analysis and generate insights.

## Project Report
The detailed project report is available in paper.pdf. It includes:

- Methodology and approaches for data cleaning and feature engineering.
- Exploratory data analysis results and visualizations.
- Key findings and recommendations for stakeholders.

---
## Conclusion
This project offers valuable insights into the adoption and distribution of Electric Vehicles (EVs), leveraging data analysis techniques to uncover trends and patterns. By cleaning and analyzing the dataset, we have identified key factors influencing EV adoption, such as geographic, economic, and legislative impacts. These findings can be used by policymakers, manufacturers, and researchers to encourage sustainable transportation solutions and improve EV accessibility.







