# Gaming User Loyalty Analysis

## Overview

This project is based on analyzing user activity data from a gaming platform to understand user behavior and calculate loyalty points. The analysis focuses on how users interact with the platform through deposits, withdrawals, and gameplay activity.

The objective is to identify high-value users and generate insights that can support better decision-making in reward distribution and user engagement.

---

## Objectives

The main objectives of this project are:

* To analyze user transactions and activity
* To calculate loyalty points using a defined approach
* To identify top-performing users
* To derive insights that can be useful for business decisions

---

## Dataset

The dataset consists of three types of user activity:

* Deposit transactions
* Withdrawal transactions
* Gameplay records

The same user can have multiple records across these datasets.

Note: The original dataset is not included in this repository due to privacy reasons.

---

## Data Preparation

Before analysis, the data was cleaned and prepared:

* Column names were standardized
* Datetime fields were converted into proper format
* Duplicate records were removed
* Missing values were handled carefully

---

## Feature Engineering

Some additional features were created to improve the analysis:

* Time slots were defined (12 AM–12 PM and 12 PM–12 AM)
* Date was extracted from datetime for daily analysis

---

## Loyalty Points Calculation

Loyalty points were calculated based on user activity, including deposits, withdrawals, and number of games played. Both financial contribution and engagement were considered to ensure a balanced evaluation.

---

## Analysis Performed

The following analysis was carried out:

* Slot-wise loyalty point calculation
* Ranking users based on total loyalty points
* Calculating average deposit amount
* Calculating average deposit per user
* Calculating average number of games played per user

---

## Bonus Distribution Approach

A balanced strategy was considered for bonus allocation among top users. The approach gives importance to both loyalty points and gameplay activity, ensuring fairness between high spenders and active users.

---

## Observations

* Users with higher gameplay activity tend to earn more points
* Financial contribution also plays a significant role
* A balance between engagement and spending is important for fair rewards

---

## Improvements Suggested

* Limit excessive weight on deposits
* Increase importance of user activity
* Normalize scores across users
* Include basic fraud detection checks

---

## Tools Used

* Excel / SQL / Python
* Data cleaning and transformation techniques
* Basic data analysis methods

---

## Conclusion

This project shows how user activity data can be used to design a simple loyalty system. The analysis highlights the importance of considering both engagement and financial behavior while evaluating users.

---

## Author

Manish Kumar Rajak
