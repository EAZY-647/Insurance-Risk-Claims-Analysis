# Strategic Data Analysis Report: Insurance Risk & Claims

## 📊 Live Dashboard
**[Click Here to View the Interactive PowerBI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZWMxMGZkYjktYzg0ZC00YTAyLWI3NmQtNjdlZmNmYmU3NzRjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

---

## Executive Summary
This repository contains the "Strategic Data Analysis Report," prepared by Ayush Kumar Sahu on October 26, 2023. The report provides a detailed analysis of our current insurance dataset, covering critical information regarding policyholders, their vehicles, and historical claim patterns.

The primary objective of this project is to structure available data into actionable insights. By understanding the correlations between customer demographics, vehicle characteristics, and claim behaviors, the organization can develop more accurate risk profiles and inform future strategic initiatives such as premium optimization and fraud detection.

## Detailed Analysis

### 1. Customer Demographics
To accurately assess risk, this project analyzes the policyholder beyond simple identification.
* **Socio-Economic Indicators:** We analyze Education and Household Income as behavioral indicators rather than just financial markers. Industry data suggests that higher education and stable incomes correlate with cautious driving and consistent payments. This allows for segmenting customers to offer tailored premium packages.
* **Personal Attributes:** We utilize Marital Status and Gender to assess lifestyle stability, noting that married individuals are statistically viewed as lower risk due to stable routines. We also use Birthdate to determine Age, noting that younger drivers (under 25) face higher premiums due to inexperience.
* **Household Structure:** A critical risk multiplier identified in the dataset is the "Kids Driving" metric. As the number of young, inexperienced drivers in a household increases, the probability of minor accidents rises proportionally.

### 2. Vehicle Risk Profile
The vehicle itself is analyzed as a major variable in the claims equation based on identification, condition, and usage.
* **Identification & Repair Costs:** The Make and Model directly influence claim severity. Luxury brands (e.g., BMW) carry significantly higher repair costs and claim amounts compared to economy brands, even for minor accidents.
* **Vehicle Age:** We calculate vehicle age using the Car Year. Older vehicles are more prone to mechanical failure and roadside assistance claims, but they are generally cheaper to replace than new cars.
* **Usage Patterns:** Usage is a critical risk factor. "Commercial Use" vehicles have the highest exposure to accidents as they are on the road during peak hours. "Personal Use" vehicles generally have the lowest mileage and risk profile.

### 3. Geographic & Environmental Factors
The analysis accounts for the environment where driving occurs.
* **Urban Zones:** These areas typically show a high claim frequency due to traffic congestion, though individual claims are often minor (fender benders).
* **Rural Zones:** These areas typically show lower frequency but potentially higher severity due to higher speeds on open roads.

### 4. Financial Analysis & Fraud Detection
The project examines the relationship between Claim Frequency and Claim Amount to determine business health.
* **Claimant Categorization:** We distinguish between frequent claimants (many small claims indicating poor habits) and severe claimants (rare but massive financial shocks).
* **Fraud Detection:** By cross-referencing financial metrics with vehicle data, we identify anomalies. For example, high claim frequency for specific car colors or unexpected claim amounts on older vehicles are flagged for investigation.

## Strategic Recommendations
Based on the data points analyzed, the following strategies are proposed for the upcoming quarter:
1.  **Dynamic Pricing Model:** Move away from flat-rate pricing to utilize a weighted risk score based on Age, Car Use, and Coverage Zone.
2.  **Targeted Family Plans:** Create specific bundles for households with "Kids Driving" that offer safety courses in exchange for premium discounts.
3.  **Portfolio Balancing:** Ensure the insurance portfolio is not over-exposed to Commercial vehicles operating in high-risk Urban zones.
