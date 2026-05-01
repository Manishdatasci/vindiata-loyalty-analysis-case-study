# Vindiata Loyalty Analysis Case Study

## Overview

This project presents an analysis of user activity data from a gaming platform with the objective of understanding user behavior and designing a fair loyalty points system. The analysis is based on deposits, withdrawals, and gameplay activity to identify high-value and highly engaged users.

The goal of this case study is to simulate a real-world business scenario where user data is used to drive better decision-making for rewards and engagement strategies.

---

## Objectives

* Analyze user activity across financial transactions and gameplay
* Calculate loyalty points using a structured approach
* Identify top users based on overall contribution
* Generate insights to support business decisions
* Propose a fair bonus distribution strategy

---

## Dataset Description

The dataset consists of three types of user activity:

* Deposit transactions (amount added by users)
* Withdrawal transactions (amount withdrawn by users)
* Gameplay records (number of games played)

Each user may have multiple records across these datasets.

---

## Data Preparation

The dataset was cleaned and prepared before analysis:

* Column names were standardized for consistency
* Datetime fields were converted into proper format
* Duplicate records were removed
* Missing values were handled appropriately

---

## Feature Engineering

To enhance the analysis, additional features were created:

* Time slots were defined:

  * Slot 1: 12 AM – 12 PM
  * Slot 2: 12 PM – 12 AM
* Date was extracted from datetime for daily-level analysis

---

## Loyalty Points Calculation

Loyalty points were calculated by considering both financial activity and user engagement. The approach includes:

* Contribution from deposit amount
* Contribution from withdrawal amount
* Difference between deposit and withdrawal counts
* Number of games played

This ensures that both spending behavior and platform engagement are reflected in the final score.

---

## Analysis Performed

The following analysis was conducted:

* Slot-wise loyalty point calculation
* Ranking users based on total loyalty points
* Average deposit amount
* Average deposit per user
* Average number of games played per user

---

## Bonus Distribution Strategy

A balanced bonus allocation approach was proposed for top users:

* 70% weight based on loyalty points
* 30% weight based on gameplay activity

This method ensures fairness by rewarding both high-value users and highly active users.

---

## Key Observations

* Users with higher gameplay activity tend to earn more loyalty points
* Financial contribution significantly impacts rankings
* A balanced approach is necessary to fairly reward different types of users

---

## Suggested Improvements

* Introduce a cap on the influence of large deposits
* Increase weight for gameplay activity
* Normalize scores across users
* Include basic fraud detection checks

---

## Tools and Technologies

* Python / Excel / SQL
* Data cleaning and preprocessing
* Basic analytical techniques

---

## Conclusion

This case study demonstrates how user activity data can be used to design a practical loyalty system. The analysis highlights the importance of balancing financial contribution with user engagement to create a fair and effective reward strategy.

---

## Author

Manish Kumar
