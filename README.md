# UPI Transactions Dashboard:
An interactive Tableau dashboard that visualizes digital payments made through UPI across various banks, cities, device types, and age groups—offering real-time insights into transaction volume and behavior.

## Short Description / Purpose
This dashboard provides a detailed overview of UPI transaction patterns segmented by age, city, payment method, and merchant. It empowers fintech analysts, developers, and business teams to detect trends, optimize user experience, and identify usage hotspots.

## Tech Stack
This project was developed using the following tools and technologies:

• 📊 Tableau Desktop – Primary data visualization and analytics platform

• 🧹 Excel (Power Query) – Source data preparation and grouping (age banding, currency normalization)

• 🌐 Mapbox Integration – Used for city-level geographic plotting

• 📁 Data Format: .xlsx for structured transactional logs

## Data Source
• Source File: UPI Transactions.xlsx

• Entries: 15,000+ UPI transaction records

• Key Columns:

  Bank Info: BankNameSent, BankNameReceived

  User Info: Gender, CustomerAge, City, DeviceType

  Transaction: TransactionType, Status, Amount, RemainingBalance, Currency

  Merchant & Payment: MerchantName, PaymentMethod, Purpose


## Business Problem
With rapid UPI adoption, payment providers need clear visibility into who transacts, how, where, and for what—so they can secure, scale, and streamline digital payments.

## Goal of the Dashboard
To create a unified visualization system that:

• Monitors total transaction volume and value across segments

• Compares merchant performance by payment method

• Analyzes demographic and regional trends

• Identifies preferred device types, purposes, and success rates

## Walkthrough of Key Visuals
• KPI Cards – No. of Transactions by Age Group

  Age Group 1: 3,000

  Age Group 2: 5,000

  Age Group 3: 12,000

• Map – Total Transaction Amount by City

📍 Delhi: ₹5,036,739

📍 Bangalore: ₹4,875,336

📍 Hyderabad, Mumbai, Chennai (also tracked)

• Bar Chart – Transaction Amount by Merchant & Payment Method

Merchants: Amazon, Flipkart, IRCTC, Swiggy, Zomato

Methods: Phone Number, QR Code, UPI ID

Shows average and total transaction amounts visually across all segments

• Dynamic Filters (Top Section)

 Bank Name Received

 Device Type

 Currency

 Purpose

 Payment Method

## Business Impact & Insights
• Merchant Insights: Zomato and Swiggy lead in transaction value via QR Code & UPI ID—good targets for offers.
• City Trends: Delhi & Bangalore dominate transaction amounts, useful for geo-targeted ads.
• Age Group Patterns: Majority of users fall into Age Group 3 (>24 years), guiding product design for that demographic.
• Device Preferences: Mobile is the dominant device, indicating mobile-first strategies are essential.
• Payment Preferences: Diverse use of UPI, QR, and Phone Numbers—systems must support all methods robustly.

![Dasboard](https://github.com/LakshmiKopparthi/UPI-Data-Analysis-Tableau-/blob/main/UPI%20Transactions%20Dashboard.png)
