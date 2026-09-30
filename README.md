# 🎁 FNP Sales Analysis Dashboard 2023 (Excel)

An interactive Excel dashboard analysing 1,000 orders and ₹35.2 lakh in revenue for an online gifting business, covering occasions, product categories, monthly trends, top products and cities.

![Dashboard preview](Fnp_Dashboard.png)

**Tools:** Microsoft Excel · Pivot Tables · Pivot Charts · Slicers · Data Cleaning

---

## 🎯 Project Objective
Analyse FNP order data and build an interactive Excel dashboard that shows what drives revenue: which occasions, categories, products and cities perform best, and how sales change over time.

## ❓ Business Questions
- How much revenue and how many orders were generated, and what is the average customer spend?
- Which occasions and product categories bring in the most revenue?
- How does revenue change across months and order times?
- Which products and cities lead?
- How long does delivery take on average?

---

## 📂 Dataset
Three linked tables, all included in this repo:

| File | Contents |
|---|---|
| `orders.csv` | Order details, including order and delivery dates |
| `customers.csv` | Customer details |
| `products.csv` | Product details, including category |

---

## 🔍 Approach
1. Loaded the orders, customers and products tables
2. Cleaned and combined them for analysis
3. Built pivot tables for each business question
4. Created pivot charts from those tables
5. Added KPI cards and slicers
6. Arranged everything into a single dashboard

---

## 📊 Dashboard Features
**KPI cards**
- Total Orders: **1,000**
- Total Revenue: **₹35,20,984**
- Average Delivery Time: **5.53**
- Average Customer Spend: **₹3,520.98**

**Charts**
- Revenue by Occasion
- Revenue by Category
- Revenue Trend by Order Time
- Revenue by Month
- Top 5 Products by Revenue
- Top 10 Cities by Orders

**Slicers:** Order Date · Delivery Date · Occasion

---

## 💡 Key Insights
- **Revenue is concentrated in a few months.** Revenue peaks in February and August, with smaller peaks in March and November, and stays much lower in the other months. This matches Valentine's Day and Raksha Bandhan season. ✔
- **Colors is the top-earning category**, ahead of Soft Toys and Sweets. ✔
- **Anniversary is the top occasion by revenue**, followed by Raksha Bandhan. ✔
- **Order volume is spread across many cities.** The top 10 cities each have fewer than 30 orders, so no single city dominates. ✔
- The top 5 products earn similar amounts, so revenue does not depend on one product. ✔

---

## ✅ Recommendations
- Plan stock, marketing and delivery capacity ahead of the February, August and November peaks.
- Promote Colors, Soft Toys and Sweets, since they lead in revenue.
- Use the slower months for occasion-based offers, such as anniversaries and birthdays, which are not tied to festivals.
- Track delivery time by city, since it directly affects gifting orders.

---

## ⚠️ Limitations
- The analysis covers 1,000 orders, so city-level counts are small and should be read with care.
- The dashboard shows patterns, not causes. For example, the seasonal peaks match festivals, but the data doesn't prove festivals are the reason.
- The dashboard has no profit or cost data, so it measures revenue, not profitability.

---

## 🛠 Tools Used
| Tool | Used for |
|---|---|
| Microsoft Excel | Analysis and dashboard |
| Pivot Tables | Summarising orders by occasion, category, month and city |
| Pivot Charts | Visualising the summaries |
| Slicers | Filtering by date and occasion |
| Data Cleaning | Preparing the raw tables |

---

## 📁 Repository Contents
- [Fnp_Analysis.xlsx](Fnp_Analysis.xlsx): the dashboard
- [Fnp_Dashboard.png](Fnp_Dashboard.png): dashboard screenshot
- [orders.csv](orders.csv) · [customers.csv](customers.csv) · [products.csv](products.csv): source data
- README.md: this file

---

## 🖱 How to Use the Dashboard
1. Download `Fnp_Analysis.xlsx` and open it in Microsoft Excel
2. Go to the dashboard sheet
3. Use the **Order Date**, **Delivery Date** and **Occasion** slicers to filter
4. The KPI cards and charts update with your selection

*Slicers and timelines work best in desktop Excel, not Excel Online or mobile.*

---

## 🧠 What I Learned
- Combining several tables into one analysis
- Building KPI cards, pivot charts and slicers into a single dashboard
- Finding seasonal patterns in sales data
- Presenting findings as insights and recommendations

---

## 🚀 Future Improvements
- Rebuild the dashboard in **Power BI** with a star-schema data model
- Query the tables with **SQL** to answer the same questions
- Use **Python (Pandas)** for cleaning and deeper analysis
- Add cost data to analyse profit, not only revenue

---

## 👤 Author
**Sarjana Dhandapani**
MBA (AI & Data Science), RV University · Bengaluru
🔗 [LinkedIn](https://www.linkedin.com/in/sarjanads) · 📧 sarjanadhp@gmail.com
