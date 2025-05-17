# 🎇 Diwali Sales Analysis Using Python

A data analysis project to analyze sales performance during the Diwali season using Python. The goal is to extract meaningful insights like top-selling products, revenue trends, customer behavior, and more.

---

## 📁 Project Structure

```
diwali_sales_analysis/
│
├── diwali_sales.csv         # Sample dataset (can be replaced with your own)
├── sales_analysis.py        # Main Python script for analysis
├── requirements.txt         # Required Python packages
├── README.md                # This file
```

---

## 🧾 Description

This project performs exploratory data analysis (EDA) on a Diwali sales dataset to:

- Understand sales trends before and after Diwali.
- Identify top-selling categories and products.
- Visualize regional performance.
- Analyze customer purchasing patterns.

---

## 🛠️ Requirements

You need the following Python libraries installed:

```bash
pandas
matplotlib
seaborn
openpyxl   # For Excel file support (if needed)
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## 📥 Dataset

The dataset (`diwali_sales.csv`) contains the following fields:

| Column Name      | Description                      |
|------------------|----------------------------------|
| Order ID         | Unique order identifier          |
| Product          | Product name                     |
| Category         | Product category                 |
| Quantity         | Number of units sold             |
| Price per Unit   | Price of each unit               |
| Date Sold        | Sale date                        |
| Region           | Customer region                  |

> You can replace this with your own dataset as long as it follows a similar structure.

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Firdous-co/diwali-sales-analysis.git
cd diwali-sales-analysis
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the analysis script:

```bash
python sales_analysis.py
```

4. View the results in the terminal or generated plots inside the `output/plots/` directory.

---

## 📊 Key Insights

The analysis provides the following insights:

- Total revenue generated during the Diwali period.
- Top 5 selling products and categories.
- Daily/monthly sales trend visualization.
- Regional comparison of sales.
- Average transaction value by category.

---

## 📷 Sample Visualizations

- Line chart: Sales over time
- Bar chart: Top selling categories
- Pie chart: Sales distribution by region
- Heatmap: Sales correlation between quantity and price

---

## 🤝 Contributing

Feel free to fork this repository or open issues if you have any suggestions or improvements!

---
