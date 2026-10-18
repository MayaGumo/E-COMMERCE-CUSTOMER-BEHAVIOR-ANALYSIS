E-Commerce Customer Behavior Analysis

Overview

This project analyzes customer demographic, spending, and engagement patterns using the E-commerce Customer Behavior.csv dataset. The goal is to identify purchasing trends, evaluate customer loyalty tiers, and measure the impact of discounts on overall spending.

Dataset Features

The dataset includes the following customer information:

Customer ID: Unique identifier for each customer

Gender: Customer gender (Female, Male)

Age: Age of the customer

City: Customer location (New York, Los Angeles, Chicago, San Francisco)

Membership Type: Loyalty tier (Gold, Silver, Bronze)

Total Spend: Total purchase amount in USD

Items Purchased: Total quantity of items bought

Average Rating: Customer feedback score on a scale of 1.0 to 5.0

Discount Applied: Whether a discount code was used (True, False)

Days Since Last Purchase: Recency of the last transaction

Satisfaction Level: Overall customer satisfaction status

Quick Start

To view and analyze the dataset using Python and Pandas:

import pandas as pd

# Load the dataset
df = pd.read_csv('E-commerce Customer Behavior.csv')

# View the first few rows
print(df.head())


Key Research Questions

How does spending differ across Gold, Silver, and Bronze membership tiers?

Are customers who receive discounts more active or frequent buyers?

How does customer age or location correlate with items purchased?

