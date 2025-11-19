# Ola-Ride-Analysis
This repository presents analysis of Ola ride data, combining Python-based data cleaning with an interactive Power BI dashboard. The aim of the project is to transform raw operational data into meaningful insights about customer behaviour, driver performance, cancellation trends, and payment patterns.
# 🚀 Project Overview
> Data Cleaning & Preprocessing (Python – Ola.ipynb)
> Importing and exploring raw ride data
> Handling missing values with appropriate strategies:
> Median imputation (Booking Value, Ride Distance)
> Mean imputation (Ratings)
> Category replacements for nulls
> Dropping unnecessary metrics (Avg VTAT, Avg CTAT)
> Standardizing categorical fields (Ride Status, Payment Method, etc.)
> Exporting a final cleaned dataset (ola_super_cleaned.csv)

# Interactive Dashboard (Power BI – ola dashboard create.pbix)
> The dashboard visualizes key business metrics, including:
> Ride Status Breakdown (Completed vs Cancelled vs Incomplete)
> Payment Method Distribution
> Driver & Customer Rating Patterns
> Cancellation Reasons by Driver & Customer
> Revenue & Booking Value Metrics
> Ride Distance Insights
> Time-based ride trends

# 🛠️ Tech Stack
> Python (Pandas, NumPy) – Data processing
> Jupyter Notebook – Cleaning workflow
> Power BI – Dashboard & reporting
> CSV – Output dataset

# 📊 Key Insights Generated
> Identified major reasons behind ride cancellations
> Highlighted patterns in incomplete rides
> Analyzed customer and driver ratings
> Compared payment method usage across rides
> Monitored booking value trends
> Provided operational metrics for business optimization
