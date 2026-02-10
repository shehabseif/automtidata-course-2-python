# Automatidata – NYC Taxi Fare Analysis (Course 2)

## Overview
This project is part of the **Google Advanced Data Analytics Professional Certificate**  
(Course 2: *Get Started with Python*).

In this scenario, Automatidata — a fictional data consulting firm — is working with the **New York City Taxi & Limousine Commission (TLC)** to prepare taxi trip data for analysis and future fare prediction modeling.

The focus of this project is **data inspection, preparation, and early analysis**, not model building.

---

## Business Objective
Prepare and inspect NYC taxi trip data to:
- Understand data structure and quality
- Identify potential anomalies
- Assess key variables relevant to fare prediction
- Communicate findings clearly to stakeholders

---

## Dataset
- **Source:** NYC Taxi & Limousine Commission (educational sample)
- **Year:** 2017
- **Rows:** ~22,699 trips
- **Columns:** 18 variables
- **Granularity:** One row per taxi trip

Key variables include:
- Trip distance
- Total fare amount
- Passenger count
- Payment type
- Vendor ID
- Pickup and dropoff timestamps

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Project Structure

├── Data/
│ └── 2017_Yellow_Taxi_Trip_Data.csv
│
├── Notebook/
│ └── Activity_Course 2 Automatidata project lab.ipynb
│
├── Executive Summary/
│ └── PACE_Strategy_and_Executive_Summary.docx
│
└── README.md



---

## Key Tasks Completed
- Loaded and inspected the dataset using pandas
- Reviewed data types, null values, and distributions
- Identified anomalies (negative fares, extreme values)
- Analyzed payment types and tipping behavior
- Compared vendors and passenger counts
- Prepared insights for future predictive modeling

---

## Key Findings (High Level)
- Most trips are short-distance (1–3 miles)
- Credit card payments dominate and include tips
- Cash trips show zero recorded tips (expected behavior)
- Some fare and total amount values are negative or extreme
- Trip distance and total amount are strong candidate features for modeling

---

## Next Steps
- Clean anomalous and invalid values
- Convert datetime fields properly
- Engineer features (trip duration, average speed)
- Proceed to exploratory data analysis (EDA)
- Build and evaluate a fare prediction model

---

## Notes
This project was completed as part of a structured learning program.  
The dataset and scenario are **for educational purposes only**.

