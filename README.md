# Fraud Detection EDA using Python

## Project Overview
This project uses Python-based exploratory data analysis (EDA) to investigate transaction patterns and identify potential fraud-risk signals. The analysis focuses on transaction behaviour, merchant activity, client-level risk indicators and seasonal patterns.

## Business Problem
Fraud and unusual transaction behaviour can create financial losses, operational workload and customer trust issues. The aim of this project is to use EDA to highlight where a risk team should investigate further, rather than to claim a fully deployed fraud prediction system.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure
```text
fraud-detection-eda-python/
├── README.md
├── PROJECT_SUMMARY.md
├── requirements.txt
├── data/
│   └── README.md
├── docs/
│   └── methodology.md
├── notebooks/
│   └── fraud_detection_eda.ipynb
└── outputs/
    └── charts/
```

## Analysis Covered
- Data understanding and cleaning
- Transaction trend analysis over time
- High-value transaction analysis
- Merchant-level transaction pattern review
- Transaction type analysis
- Top client analysis
- Unique card usage by client
- High-risk client categorisation
- Monthly spending pattern analysis for high-risk clients

## Key Business Insights
- High-value transaction activity can vary meaningfully by month, making seasonal monitoring useful.
- Certain merchants and clients show substantially higher transaction volumes, making them useful targets for deeper risk review.
- Online transaction behaviour can be used as a screening feature for potential high-risk clients.
- Fraud monitoring should combine transaction value, channel behaviour, merchant concentration and client-level patterns.

## How to Run
Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook notebooks/fraud_detection_eda.ipynb
```

## Dataset Note
The original dataset is not redistributed in this repository. The notebook references a transaction fraud dataset source, and the `data/README.md` file explains how the data folder should be structured if the dataset is downloaded separately.

## Recruiter Summary
This project demonstrates Python EDA, data cleaning, risk-focused analysis and business interpretation for fraud monitoring use cases.
