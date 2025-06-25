# -ETL_pipeline_project_01
🚀 Built End-to-End ETL Pipeline: From Messy Restaurant Data to Cloud Analytics
SITUATION 📊
I recently tackled a real-world data challenge: transforming 10,000+ messy restaurant review records into a clean, analytics-ready dataset. The raw data was plagued with missing values, inconsistent formatting, and corrupted columns - a perfect scenario to demonstrate ETL best practices.
TASK 🎯
My goal was to build a complete data pipeline that could:

Extract data from CSV sources
Clean and transform messy restaurant review data
Load processed data into Google BigQuery for analysis
Create a reusable, scalable ETL workflow

ACTION ⚡
Here's what I built using Python, Pandas, and Google Cloud:
🔍 EXTRACT Phase:

Loaded 10K restaurant reviews from CSV
Performed initial data profiling and quality assessment

🛠️ TRANSFORM Phase:

Removed corrupted columns and handled 45+ missing reviews
Converted data types (strings to datetime, ratings to numeric)
Parsed metadata to extract reviewer stats (review count, followers)
Applied data validation and error handling

📤 LOAD Phase:

Authenticated with Google Cloud Platform
Pushed clean dataset to BigQuery data warehouse
Created reusable functions for automated pipeline execution

💡 Technical Stack:

Python (Pandas, pandas-gbq)
Google Cloud BigQuery
Data validation & error handling
ETL pipeline simulation with logging

RESULT 📈
✅ Successfully processed 8,381 clean records (16% data quality improvement)
✅ Built reusable ETL functions with proper logging
✅ Deployed dataset to cloud for scalable analytics
✅ Created foundation for restaurant sentiment analysis & business intelligence
Key Insights from the Data:

Average rating: 4.2/5 stars across all restaurants
100 unique restaurants analyzed
6,150+ unique reviewers contributing insights


🎯 WHAT'S NEXT?
I'm actively seeking Data Analyst and Cloud Data Analyst opportunities where I can apply these ETL skills to drive business insights. This project demonstrates my ability to:

Handle messy, real-world data
Build scalable cloud data pipelines
Apply data engineering best practices
Deliver clean datasets for analytics teams
