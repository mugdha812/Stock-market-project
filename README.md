# Real-Time Stock Market Data Pipeline using Kafka & AWS
This project is a hands-on implementation of a **real-time data pipeline** simulating stock market data streaming. It demonstrates how raw, high-frequency data can be ingested, processed, stored, and queried using a modern data engineering stack.

##  Project Overview
The goal was to simulate a live stock market feed and build a complete data pipeline that handles real-time data—from ingestion to warehousing to querying.

## Tech Stack
- **Programming Language:** Python  
- **Streaming Framework:** Apache Kafka, Zookeeper  
- **Cloud Services (AWS):**
  - EC2 (Kafka server hosting)
  - S3 (object storage for ingested data)
  - Glue Crawler + Glue Catalog (schema detection & metadata management)
  - Athena (querying S3 data with SQL)

## Architechture
![Architecture](https://github.com/user-attachments/assets/d210cfe1-3312-461d-92ba-48cbf70fe2ca)

 
  ##  Acknowledgements
  Thanks to the tutorial by [https://www.youtube.com/@DarshilParmar] for the guided walkthrough and dataset inspiration.
