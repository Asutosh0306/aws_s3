# Cloud-Native Analytics Pipeline on AWS 🚀

A fully serverless, cloud-native data analytics pipeline built on AWS — transforming raw Superstore sales data into interactive business intelligence dashboards using:

- **Amazon S3** for data storage
- **AWS Glue** for ETL and job orchestration
- **Amazon Athena** for serverless SQL querying
- **Amazon QuickSight** for data visualization

---

## 📊 Project Overview

This project simulates a real-world analytics pipeline where:
- Raw sales data is uploaded to an S3 bucket
- Glue jobs clean, transform, and partition the data
- Athena queries run on the curated dataset
- QuickSight dashboards provide real-time insights

---

## 🛠️ Technologies Used

| Service     | Purpose                         |
|-------------|---------------------------------|
| Amazon S3   | Storage for raw and processed data |
| AWS Glue    | ETL transformation + Data Catalog |
| Amazon Athena | Serverless querying (SQL over S3) |
| QuickSight  | Business intelligence dashboards |

---

## 🗺️ Architecture

![Architecture Diagram](architecture.png)

---

## 📁 Project Structure

```bash
scripts/         # Glue ETL scripts
dashboard/       # Screenshots or exported dashboards
data/            # Sample CSVs or schema info
