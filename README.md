# data-analyst-juhi
# 🚧 Operating Permit Dataset – AWS Portfolio EDA Project

## 📌 Objective

This project performs Exploratory Data Analysis (EDA) on an Operating Permit dataset to understand permit trends, handle missing data, and support AWS-based ETL workflows.

## 📁 Dataset

The dataset contains structured information about permits including:
- Permit types
- Approval dates
- Work descriptions
- Issuing authorities
- and more...

> 📄 File: `operating_dataset.csv`

## 🔧 Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- AWS Glue DataBrew (mentioned in the report)

## 🧠 Insights Uncovered

- Missing data patterns
- High-cardinality fields
- Distribution of permit types
- Initial correlation analysis

## 📊 EDA Focus Areas

- Missing data handling
- Frequency and value counts
- Data types and normalization
- Heatmaps, bar charts, and summary statistics

## 💻 How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/operating_permit_eda.ipynb
