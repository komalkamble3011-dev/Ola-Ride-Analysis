# Ola-Ride-Analysis
This repository presents analysis of Ola ride data, combining Python-based data cleaning with an interactive Power BI dashboard. The aim of the project is to transform raw operational data into meaningful insights about customer behaviour, driver performance, cancellation trends, and payment patterns.
# 🚀 Project Overview
# Data Cleaning & Preprocessing (Python – Ola.ipynb)
1.Importing and exploring raw ride data
2.Handling missing values with appropriate strategies:
  i)Median imputation (Booking Value, Ride Distance)
  ii)Mean imputation (Ratings)
  iii)Category replacements for nulls
3.Dropping unnecessary metrics (Avg VTAT, Avg CTAT)
4.Standardizing categorical fields (Ride Status, Payment Method, etc.)
5.Exporting a final cleaned dataset (ola_cleaned.csv)



# Interactive Dashboard (Power BI – ola dashboard create.pbix)
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
