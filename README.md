# foodpanda-data-science-
Foodpanda Data Analysis Project
This project provides a comprehensive analysis of customer behavior, sales trends, and operational performance using a Foodpanda dataset. The analysis is implemented in Python and focuses on data cleaning, processing, and generating actionable insights exported to a multi-sheet Excel report.

## Project Overview
The primary goal of this project is to analyze 6,000 order records to understand regional performance, popular food categories, and customer loyalty trends. It evaluates key metrics such as total revenue, average ratings, and delivery efficiency across various cities in Pakistan.

### Key Features
Data Cleaning: Automated conversion of date columns (signup_date, order_date, etc.) and data type verification.

Sales Engineering: Calculation of a total_sales metric derived from item quantity and price.

Regional Insights: Performance breakdown for major cities including Multan, Lahore, Peshawar, Islamabad, and Karachi.

Operational Analysis: Detailed reports on delivery status (Delivered vs. Delayed vs. Cancelled) and payment method preferences (Cash, Wallet, Card).

Customer Segmentation: Analysis of active vs. inactive (churned) users and identification of the top 10 customers by total spend.

Trend Analysis: Monthly revenue tracking from August 2023 through August 2025.

### Technology Stack
Language: Python

Libraries: * pandas: For data manipulation and aggregation.

openpyxl: Used for exporting reports to Excel.

Environment: Google Colab / Jupyter Notebook

### Dataset Insights
The analysis is performed on the Foodpanda Analysis Dataset, which includes:

6,000 Total Entries

20+ Features, including customer demographics, restaurant details (KFC, Pizza Hut, Subway, etc.), food categories, and loyalty points.

### How to Use
Clone the Repository:

Bash
git clone https://github.com/sajid-ahsan-seyam-26/foodpanda-data-science-.git

# Install Dependencies:

Bash
pip install pandas
Run the Notebook:
Open foodpanda.ipynb in Jupyter or Google Colab.

Upload Dataset:
Ensure Foodpanda Analysis Dataset.csv is uploaded when prompted by the script.

Generate Report:
The script will automatically generate foodpanda_analysis_report.xlsx containing all summarized data.

### Author
Sajid Ahsan Seyam

GitHub: sajid-ahsan-seyam-26
