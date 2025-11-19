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
1.Ride Status Breakdown (Completed vs Cancelled vs Incomplete)

2.Payment Method Distribution

3.Driver & Customer Rating Patterns

4.Cancellation Reasons by Driver & Customer

5.Revenue & Booking Value Metrics

6.Ride Distance Insights

7.Time-based ride trends

# 🛠️ Tech Stack
1.Python (Pandas, NumPy) – Data processing

2.Jupyter Notebook – Cleaning workflow

3.Power BI – Dashboard & reporting

4.CSV – Output dataset

# 📊 Key Insights Generated
1.Identified major reasons behind ride cancellations

2.Highlighted patterns in incomplete rides

3.Analyzed customer and driver ratings

4.Compared payment method usage across rides

5.Monitored booking value trends

6.Provided operational metrics for business optimization
