# 🛍️ National Clothing Chain Analysis

A Power BI dashboard analyzing 6 months of retail data from a US national clothing chain — uncovering revenue trends, customer behavior, product performance, and inventory insights to support business decision-making.

---

## 📌 Business Questions

1. How does revenue change over time, by location, and by influencing factors?
2. What strategies can optimize revenue and improve customer retention?
3. How can customers be segmented by geography, income, and spending behavior?
4. Which products and regions should be prioritized for inventory and marketing?

---

## 📊 Dataset

| Detail | Value |
|---|---|
| Period | September 2020 – March 2021 |
| Customers | 1,000 across 51 US states |
| Products | 17 items |
| Total Revenue | $285,905.10 |

---

## 🗂️ Dashboard Structure

The report is organized into **4 tabs:**

### 1. Overview
High-level KPIs, customer distribution map across US states, and daily revenue trend over 6 months.

### 2. Sales
- Revenue trend with B-Spline confidence interval
- Top 5 states by revenue (donut chart)
- Monthly sale distribution (boxplot)
- Correlation between customer count and total sales by state

### 3. Products
- Stock quantity per product (bar chart)
- Customer rating vs. return rate (scatter plot)
- Correlation heatmap: Price · Rating · Stock · Return Rate

### 4. Customers
- Customer distribution by state and income tier (5 segments)
- Daily customer traffic trend
- Top 5 highest spenders with state breakdown

---

## 🔍 Key Findings

**Revenue is seasonal and event-driven.**
Revenue peaked in September ($113K — Back-to-School), spiked again in December ($88K — Black Friday + holiday shopping), then dropped sharply from January to March. Without targeted campaigns, revenue is projected to remain flat.

**California dominates — but income profiles vary by state.**
California contributes 22.4% of total revenue and holds 15% of all customers. However, income analysis reveals California and New York skew high-income (23–27% high earners), while Florida, Texas, and Illinois are predominantly mid-to-low income (74%+). Product strategy should be differentiated accordingly.

**Customer rating is the strongest predictor of return rate.**
Higher-rated products have significantly lower return rates. Price, however, shows weak correlation with returns — meaning product quality matters more than pricing when it comes to reducing returns.

**Revenue is proportional to customer volume.**
States with more customers consistently generate more revenue — suggesting that customer acquisition campaigns (referral programs, membership cards, regional promotions) are the most direct lever for revenue growth.

**Top spenders are concentrated in Illinois and New Jersey.**
The top 5 highest-spending customers are all from Illinois (3) and New Jersey (2), contributing $13,609.52 combined. These VIP customers warrant personalized retention strategies.

---

## 💡 Business Recommendations

| Area | Recommendation |
|---|---|
| Seasonal strategy | Maximize Back-to-School (Sep) and Holiday (Dec) with targeted promotions; introduce Halloween Sales and New Year Deals to reduce off-peak drops |
| Product segmentation | Push premium products in California & New York; offer affordable bundles and promotions in Florida, Texas & Illinois |
| Inventory | Clear high-stock items (Long Dress, Sweater Dress >300 units) via flash sales; adjust reorder strategy for slow-moving SKUs |
| Customer retention | Build loyalty program with points and VIP tiers; personalize outreach for top spenders |
| Return rate | Focus quality improvement on low-rated products; analyze high-return SKUs and address root causes |

---

## 🛠️ Tools & Techniques

- **Power BI** — Dashboard design, DAX measures, interactive visuals
- **Power Query** — Data transformation: unpivot transaction table, income bin segmentation (5 tiers), date formatting
- **Visualization types used:** Map, Line chart, Donut chart, Boxplot, Scatter plot, Correlation heatmap, Bar chart, KPI cards

---

## 📁 Files

```
├── baocao.pbix        # Power BI report file
├── Report.pdf         # Full analysis report with insights
└── README.md
```



**Nguyễn Phúc Loan**
Data Science — HCM University of Science, Vietnam National University
[LinkedIn](https://linkedin.com/in/nguyenphucloan) · [GitHub](https://github.com/NguyenPhucLoan)
