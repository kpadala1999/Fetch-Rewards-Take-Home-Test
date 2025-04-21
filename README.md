# Fetch-Rewards-Take-Home-Test
This repository contains my completed take-home assignment for the Data Analyst position at Fetch. The exercise shows my approach to data exploration, SQL query design, insights generation, and stakeholder communication. The goal was to evaluate data quality, answer business questions with SQL, and communicate results clearly to a non-technical audience.
Assignment Steps
1. Data Exploration
Using Python, I explored three datasets: PRODUCTS_TAKEHOME, TRANSACTIONS_TAKEHOME, and USERS_TAKEHOME.
Key tasks completed:
Validated data types, parsed dates, and inspected value distributions.
Identified missing, null, duplicate, and invalid entries.

Findings:

Missing Values: Multiple fields across all datasets lacked data (CATEGORY_1–CATEGORY_4, MANUFACTURER, GENDER, BARCODE).

Invalid Fields: Some dates could not be parsed and were converted to NaT; numeric anomalies were found in FINAL_SALE.

Unclear Columns: Fields like SCAN_DATE vs PURCHASE_DATE

These issues were formally documented in Question 1.docx

2. SQL Queries
I addressed both closed-ended and open-ended business questions using SQL in Sql queries.html

3. Communication with Stakeholders
To translate technical results into actionable insights, I crafted a  mail to stakeholder

Included in Message to Stakeholders.docx, this document:

Summarizes data quality concerns.

Highlights a key finding: strong performance of private-label products among power users.

Requests clarification on unclear fields and access to metadata or business rules.

Targets communication to the data governance and product operations teams.

