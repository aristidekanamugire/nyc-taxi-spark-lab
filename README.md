# nyc-taxi-spark-lab
PySpark analysis of 3M+ NYC Yellow Taxi trips (Jan 2023) – Lab 7 Full Spark workflow: Parquet ingestion, feature engineering, joins, window functions, data quality, caching &amp; performance tests. Includes clean report + screenshots.
# NYC Taxi Spark Lab (Jan 2023) – Lab 7

Analysis of **3.07 million** NYC yellow taxi trips using **PySpark** (Google Colab).  
From raw Parquet to production-style insights – all in one notebook.

### What This Lab Covers
- Parquet + schema-on-read (zero manual parsing)
- Feature engineering: trip duration & tip percentage
- Join with taxi zone lookup (real neighborhood names)
- Window functions: Top 3 rush hours per day of week
- Data quality filtering (only ~2.7% rows removed!)
- Caching & repartitioning speed test (8–10× speedup)
- Stretch: Union Jan+Feb 2023 + payment type by borough

### Key Results
- Busiest hour: **Tuesday 6 PM** (36,405 pickups)  
- #1 pickup zone: **Upper East Side** (Manhattan)  
- Caching turns 5-second queries into **0.5 seconds**

### Files
- `NYC_Taxi_Spark_Lab.ipynb` – Complete notebook (all cells working)
- `report/`  
  - `Lab7_NYC_Taxi_Spark_Report.pdf` – Final submission (title page + screenshots)
  - Screenshots: Top zones • Rush hours • Caching test
- `data/` (not uploaded – 240 MB)  
  Links in notebook:
  - https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2023-01.parquet
  - https://d37ci6vzurychx.cloudfront.net/misc/taxi_zone_lookup.csv

### Run It Yourself
1. Open in [Google Colab](https://colab.research.google.com/github/your-username/nyc-taxi-spark-lab/blob/main/NYC_Taxi_Spark_Lab.ipynb)
2. Run all cells – works 100% as of November 2025

### Why Spark Wins
> “Same Pandas-style code. Zero crashes. 10× faster with caching.”  
> This lab turned me from a Spark skeptic into a believer.

**Lab 7 – 10/10 ready to submit**

---
Made with frustration (Colab crashes) and victory (Spark actually works)  
[Your Name] – November 2025
