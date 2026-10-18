E-Commerce Customer Behavior Analysis

Overview

This repository contains data and analysis for understanding customer demographics, spending patterns, and engagement levels based on the E-commerce Customer Behavior.csv dataset. The goal of this project is to evaluate purchasing habits, discount utilization, and customer loyalty across different regions and membership tiers.

Dataset Schema

The main dataset E-commerce Customer Behavior.csv contains the following attributes:

Column Name

Type

Description

Customer ID

Integer

Unique identifier for each customer

Gender

Text

Customer gender (Female, Male)

Age

Integer

Age of the customer

City

Text

Customer location (New York, Los Angeles, Chicago, San Francisco, etc.)

Membership Type

Text

Loyalty membership status (Gold, Silver, Bronze)

Total Spend

Numeric

Total amount spent by the customer ($)

Items Purchased

Integer

Total count of items purchased

Average Rating

Numeric

Customer's average feedback score (1.0 - 5.0)

Discount Applied

Boolean

Indicates if a discount was applied (True / False)

Days Since Last Purchase

Integer

Recency in days since the last transaction

Satisfaction Level

Text

Customer feedback status (Unsatisfied, Neutral, Satisfied)

Sample Data Preview

Customer ID

Gender

Age

City

Membership Type

Total Spend

Items Purchased

Average Rating

Discount Applied

Days Since Last Purchase

101

Female

29

New York

Gold

1120.20

14

4.6

True

25

102

Male

34

Los Angeles

Silver

780.50

11

4.1

False

18

103

Female

43

Chicago

Bronze

510.75

8

3.4

True

42

104

Male

30

San Francisco

Gold

1460.30

19

4.7

False

12

Setup & Usage

Prerequisites

Python 3.8+

Pandas

Running the Analysis

Clone the repository:

git clone https://github.com/your-username/ecommerce-customer-behavior.git
cd ecommerce-customer-behavior


Load the dataset using Pandas:

import pandas as pd

# Load data
df = pd.read_csv('E-commerce Customer Behavior.csv')

# Preview data
print(df.head())


Key Analysis Questions

Membership Impact: How significantly does Total Spend differ across Gold, Silver, and Bronze membership tiers?

Discount Effect: Does applying discounts increase overall purchasing frequency or average rating?

Recency & Churn: What is the relationship between Days Since Last Purchase and overall customer satisfaction?
