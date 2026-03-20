# 📈 Amazon Sales Performance Analysis

An end-to-end data analysis project examining Amazon sales data to uncover operational inefficiencies, cancellation patterns, and sales trends — with cloud integration via AWS S3.

---

## 🎯 Project Overview

This project simulates a real-world business analytics scenario: a data analyst is tasked with understanding why orders are being cancelled, which product categories drive revenue, and how logistics performance varies across fulfillment channels.

---

## 📊 Key Analyses

| Analysis | Description |
|----------|-------------|
| **Category Analysis** | Identified top-selling and highest-revenue product categories |
| **Cancellation Analysis** | Calculated total financial impact of cancelled orders by category |
| **Logistics Performance** | Compared carrier and fulfillment method performance |
| **Channel Distribution** | Visualized sales breakdown by channel (Amazon.in vs. others) |

---

## 🔍 Key Findings

- **High Cancellation Risk:** "Set" and "Kurta" categories show disproportionately high cancellation rates — stock and quality control processes should be reviewed.
- **Financial Impact:** Quantified the total revenue loss from cancellations, enabling data-driven prioritization.
- **Sales Concentration:** Amazon.in is the dominant sales channel, representing the majority of total order volume.

---

## ☁️ Cloud Integration (AWS)

- Raw dataset uploaded and stored in **AWS S3** as part of a cloud-based data pipeline workflow.
- Analysis was performed on data retrieved from S3, reflecting a real-world cloud data environment.
- Explored **AWS Glue** for ETL transformation as part of ongoing cloud learning.

---

## 🛠️ Technologies Used

- **Python** — Core analysis language
- **Pandas** — Data cleaning, manipulation, and aggregation
- **Matplotlib & Seaborn** — Data visualization
- **AWS S3** — Cloud storage and data pipeline integration
- **AWS Glue** — ETL exploration
- **Google Colab** — Development environment
- **GitHub** — Version control and project documentation

---

## 🚀 How to Run

1. Clone this repository
2. Unzip `amazon_data.csv.zip`
3. Open `project.ipynb` in Google Colab or Jupyter Notebook
4. Run all cells sequentially

---

## 📁 Project Structure

```
amazon-satis-analizi/
│
├── project.ipynb         # Main analysis notebook
├── amazon_data.csv.zip   # Raw dataset
└── README.md             # Project documentation
```

---

## 👩‍💻 About

This project is part of an ongoing data & cloud learning journey, combining Python-based analysis with AWS cloud fundamentals.

**Author:** Eda Arslan  
**LinkedIn:** [linkedin.com/in/edarsllnn](https://linkedin.com/in/edarsllnn)  
**GitHub:** [github.com/edarsllnn](https://github.com/edarsllnn)

