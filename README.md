# My First Big Data Project: NYC Taxi Analysis

This is my beginner project showing how to analyze a **large dataset** (3 million taxi rides) using **PySpark**. It demonstrates scalability—PySpark handles big files by splitting them and processing in parallel!

## What It Does
- Loads NYC taxi data (Jan 2023).
- Cleans it (removes bad rows).
- Finds insights: Average fares by hour (peak at evening rush!).
- Makes a chart.

**Run Time:** 2 minutes in Google Colab. No install needed!

## How to Run (Super Easy)
1. Download data: [yellow_tripdata_2023-01.parquet](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) (150 MB).
2. Open [Google Colab](https://colab.research.google.com).
3. Upload the data file to Colab.
4. Copy-paste the code from `simple_nyc_taxi_analysis.ipynb` into a new notebook.
5. Run cells one by one—see the chart and insights!

## Key Insights
- Average taxi fare: ~$14.
- Peak hour: 5-7 PM (rush hour, higher prices).
- Total rides analyzed: 3,000,000+.

## Why PySpark?
For small data, use Pandas. For big data (like this), PySpark scales: It uses multiple computer parts (or cloud servers) to go faster. Great for jobs!

First project—learning big data! 🚀
