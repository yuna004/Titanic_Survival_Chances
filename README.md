# Titanic: Chances of Survival

A collaborative statistical analysis exploring the factors that influenced survival rates during the Titanic disaster. This project goes beyond simple data visualisation by using **Hypothesis Testing (t-tests)** to statistically validate trends related to gender, age, and passenger class.

## Overview
We analysed a dataset of 891 passengers to determine if survival was truly random or if specific demographics had a statistically significant advantage. This project demonstrates the application of the scientific method to historical data to uncover social patterns in crisis situations.

## Tech Stack
* **Language:** R
* **Environment:** R Markdown
* **Statistical Methods:** Two-sample T-tests, Null Hypothesis Testing ($H_0$ vs $H_1$)
* **Data Handling:** Base R, Kaggle Titanic Dataset

## Key Features
* **Rigorous Hypothesis Testing:** Applied t-tests to compare survival means across different groups (e.g., Women vs. Men, 1st Class vs. 3rd Class).
* **Demographic Segmentation:** Analysed survival chances specifically for children (<18), adults (18-50), and the elderly (>50).
* **Validation:** Proved that factors like gender and class were not independent of survival, confirming historical "women and children first" protocols with a 95% confidence level.
* **Bonus Analysis:** Includes a fun "Rose vs. Jack" scenario analysis based on the statistical averages of their respective demographics.
* **Critical Decision Making:** The analysis highlights how socioeconomic status (Class) directly correlated with survival, a key study in resource allocation during emergencies.
* **Team Collaboration:** Successfully managed a joint codebase and report structure within a 3-person team.
* **Model Accuracy:** Verified that survival was heavily dependent on identified variables, rejecting the null hypothesis across all primary tests.
