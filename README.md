# 📊 CodeAlpha Sales Analytics Dashboard  

<div align="center">

![Domain](https://img.shields.io/badge/Domain-Data%20Analytics-blue)
![Tool](https://img.shields.io/badge/Tool-Python-yellow)
![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Matplotlib-green)
![Visualization](https://img.shields.io/badge/Visualization-Seaborn-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

</div>

---

# 📌 Project Overview

This project presents a complete sales analysis and data visualization dashboard using the Superstore dataset.

The dashboard transforms raw business data into meaningful visual insights to help understand:
- Sales performance
- Profit trends
- Regional performance
- Customer purchasing behavior
- Product category performance

The project was completed as part of the **CodeAlpha Data Analytics Internship**.

---

# 🎯 Project Objectives

✔ Analyze overall sales and profit performance  
✔ Identify top-performing product categories  
✔ Understand monthly sales trends  
✔ Compare regional business performance  
✔ Create attractive and meaningful visualizations  
✔ Generate business insights for decision-making  

---

# 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|------|------|
| 💰 Total Sales | **2.29M+** |
| 📈 Total Profit | **286K+** |
| 📦 Total Orders | **5000+** |
| 🛒 Top Category | **Technology** |
| 🌍 Best Region | **West** |

---

# 📈 Dashboard Features

## 🛍 Sales Analysis
- Category-wise sales comparison
- Top-selling products
- Monthly sales trend analysis

### Highlights
- Technology category generated highest sales
- Phones and Chairs were top-selling products
- Sales increased during year-end months

---

## 🌍 Regional Performance Analysis

### Regional Insights
| Region | Performance |
|--------|-------------|
| West | Highest Profit |
| East | Strong Sales |
| Central | Moderate Performance |

---

## 📅 Monthly Sales Trend

Peak sales observed during:
- November
- December

Business activity remained consistent throughout the year.

---

# 🧠 Key Business Insights

## 1️⃣ Technology Leads Sales
- Technology products generated maximum revenue.
- Indicates high customer demand for electronic products.

---

## 2️⃣ Discounts Reduce Profit
- Higher discounts negatively impacted profit margins.
- Better discount strategies can improve profitability.

---

## 3️⃣ Regional Performance Difference
- West region contributed highest profit share.
- Central region showed lower performance compared to others.

---

## 4️⃣ Seasonal Sales Growth
- Sales increased significantly during festive and year-end periods.
- Businesses can improve inventory planning during peak months.

---

# 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Data Analysis |
| Pandas | Data Cleaning & Processing |
| Matplotlib | Data Visualization |
| Seaborn | Attractive Charts |
| GitHub | Project Hosting |

---

# 📂 Project Files

```text
CodeAlpha_Sales_Analytics_Dashboard/
│
├── Dataset/
│   └── Sample - Superstore.csv
│
├── Dashboard/
│   └── visualization.py
│
├── Images/
│   └── Dashboard Screenshots
│
├── README.md
│
└── Charts/
```

---

# 📸 Dashboard Preview
![Alt text](https://github.com/dinutanwar/CodeAlpha_Sales_Analytics_Dashboard/blob/4ff76b9a31abf851cfc310ccf9b1a804f576d7c7/image/Screenshot%202026-05-25%20195622.png)
![Alt text](https://github.com/dinutanwar/CodeAlpha_Sales_Analytics_Dashboard/blob/4ff76b9a31abf851cfc310ccf9b1a804f576d7c7/image/Screenshot%202026-05-25%20195632.png)
![Alt text](https://github.com/dinutanwar/CodeAlpha_Sales_Analytics_Dashboard/blob/4ff76b9a31abf851cfc310ccf9b1a804f576d7c7/image/Screenshot%202026-05-25%20195642.png)
![Alt text](https://github.com/dinutanwar/CodeAlpha_Sales_Analytics_Dashboard/blob/4ff76b9a31abf851cfc310ccf9b1a804f576d7c7/image/Screenshot%202026-05-25%20195655.png)
![Alt text](https://github.com/dinutanwar/CodeAlpha_Sales_Analytics_Dashboard/blob/4ff76b9a31abf851cfc310ccf9b1a804f576d7c7/image/Screenshot%202026-05-25%20195706.png)




---

# 🚀 How to Run the Project

## Step 1
Install required libraries

```bash
pip install pandas matplotlib seaborn
```

## Step 2
Download and place dataset:
`Sample - Superstore.csv`

inside the project folder.

---

## Step 3
Run Python file

```bash
python visualization.py
```

---

# 💻 Sample Python Analysis

```python
import pandas as pd

# Load dataset
df = pd.read_csv("Sample - Superstore.csv", encoding='latin1')

# Total sales by category
sales = df.groupby('Category')['Sales'].sum()

print(sales)
```

---

# 📌 Future Improvements

- Interactive dashboard integration
- Real-time sales monitoring
- Power BI dashboard version
- Advanced business forecasting
- Machine learning sales prediction

---

# 🤝 Contributing

Suggestions and improvements are welcome.  
Feel free to fork this repository and improve the project.

---

# 📧 Contact

👤 Dinesh Tanwar  
🎓 BCA AI & ML Student  
📊 Aspiring Data Analyst | Power BI Developer  

---

<div align="center">

## ⭐ If you found this project useful, give it a star on GitHub!

</div>
