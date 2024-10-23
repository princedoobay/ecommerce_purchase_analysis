# E-commerce Dataset Analysis
This repository contains an e-commerce dataset and the analysis performed to uncover various insights related to customer behavior, purchase trends, and potential fraud risks.

# Dataset Description
The dataset includes information about online purchases made by customers. It contains various columns that provide insights into customer demographics, payment details, and purchasing patterns.

# Column Descriptions
- Address: The customer's address.
- Lot: Lot number associated with the purchase.
- AM or PM: Indicates whether the purchase was made in the morning (AM) or evening (PM).
- Browser Info: Information about the browser used for the purchase.
- Company: The company where the customer is employed.
- Credit Card: The credit card number used for the purchase.
- CC Exp Date: Expiration date of the credit card.
- CC Security Code: The security code associated with the credit card.
- CC Provider: The credit card service provider (e.g., Visa, Mastercard).
- Email: Customer's email address.
- Job: Customer's profession.
- IP Address: The IP address from which the purchase was made.
- Language: Preferred language of the customer.
- Purchase Price: The amount spent on the purchase.

# Data Loading and Overview
The project begins by loading the dataset using the Pandas library and displays the top and bottom 10 rows to provide a quick overview of the data.

# Data Exploration
The project examines the data types of each column, checks for null values, and determines the number of rows and columns in the dataset. This step is crucial for understanding the structure and completeness of the data.

# Purchase Price Analysis
The analysis includes finding the highest and lowest purchase prices, as well as calculating the average purchase price. These metrics provide insights into the pricing patterns of the ecommerce purchases.

# Language and Job Title Analysis
The project explores the language distribution of customers and identifies individuals with French as their language. Additionally, it identifies individuals with "Engineer" in their job title, showcasing the diversity of professions in the dataset.

# Email and Credit Card Analysis
The analysis involves finding the email of a person with a specific IP address, identifying individuals with Mastercard as their credit card provider who made purchases above $50, and finding the email of a person with a specific credit card number.

# Time and Date Analysis
The project investigates the time distribution of purchases, categorizing them into AM and PM. This provides insights into the temporal trends of ecommerce transactions.

# Credit Card Expiry and Email Provider Analysis
The analysis identifies the number of people with credit cards expiring in 2020, providing a glimpse into upcoming expirations. Additionally, the top 5 most popular email providers are determined, giving an overview of the dominant email platforms among customers.
se Price: The amount spent on the purchase.
# Intermediate level Analysis

# Analysis Questions
The analysis focuses on answering the following questions:
# Customer Analysis:
- What is the average purchase price for each job category?
- Are there any patterns in spending behavior based on the customer's language?
# Credit Card Insights:
- Which credit card providers are most frequently used?
- Are there any patterns related to credit card expiration dates?
# Geographical Analysis:
- Does the location (address or IP address) correlate with purchase price?
- Are specific regions more active in terms of purchases?
# Security Insights:
- Are there patterns in credit card security codes indicating potential fraud?
- Do certain companies show higher security risks?
# Email and Browser Behavior:
- Do certain email domains correspond to higher spending?
- Are there specific browsers associated with higher purchase amounts?
