# AWS-Quicksight-Data-Visualization
Created data visualizations using Amazon S3 and Amazon QuickSight, working with a dataset to analyze global visa-free travel trends.

![AWS_Pro](https://github.com/user-attachments/assets/302d0181-e8f8-424d-bccd-a042953f9793)

## 📖 Overview
This project utilizes **AWS QuickSight** and **Amazon S3** to analyze and visualize data on visa-free travel access across different countries. The dataset ranks global passports based on their international mobility.

## 📂 Dataset 
- **Source**: [Kaggle - Visa-Free Countries Dataset 2024](https://www.kaggle.com/datasets/bhadramohit/visa-free-countries-dataset2024)
- **Format**: CSV
- **Fields**: Country, Passport Rank, Visa-Free Access Count

## 🚀 Steps to Run This Project
### 1️⃣ Set Up AWS QuickSight
- Sign into your **AWS Free Tier Account** ([Guide](🔐 Guide to Signing into AWS Free Account.pdf)).
- Create an **S3 bucket** and upload:
  - `visa_free_countries_dataset.csv`
  - `manifest.json`
- Set up **AWS QuickSight** and connect it to **S3**.

### 2️⃣ Visualizing Data
- Use **QuickSight** to create:
  - **Bar Chart**: Visa-Free Access by Country
  - **Pie Chart**: Global Passport Rankings

## 📊 Data Visualizations
### 📌 Bar Chart for Visa-Free Access by Country
- X-Axis: **Country**
- Y-Axis: **Visa-Free Access Count**
- Sorted in **Descending Order**

### 📌 Pie Chart for Global Passport Rankings
- Grouped by **Rank**
- Summarized **Visa-Free Access Count**
- Highlights top-ranking passports

## 📜 Files in this Repository
| File | Description |
|------|------------|
| `visa_free_countries_dataset.csv` | Raw dataset |
| `manifest.json` | AWS QuickSight manifest file |
| `🚀 AWS Data Visualization Project.pdf` | Step-by-step project guide |
| `🔐 Guide to Signing into AWS Free Account.pdf` | AWS setup instructions |
| `README.md` | This document |

## 📌 Dependencies
- AWS Account
- AWS S3 Bucket
- AWS QuickSight Subscription

📌Note: Exploring AWS services through hands-on projects like this one as a way of learning and growing my skills.
