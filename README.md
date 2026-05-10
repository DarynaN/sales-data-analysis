# Sales Data Analysis

Exploratory analysis of a multi-category retail dataset covering sales performance across countries, regions, product categories, and sales channels.

---

## Business Questions

1. Which product categories drive the most revenue and profit?
2. Which countries and regions are most efficient in terms of profit margin?
3. Do online and offline channels perform differently?
4. How does delivery time vary across categories and countries — and does it affect profit?
5. Are there weekly or seasonal patterns in sales?

---

## Dataset

- Source: Google Drive (CSV)
- Dimensions: Order ID, Country, Product Category, Sales Channel, Units Sold, Unit Price, Unit Cost
- Period: 2012–2017
- Geography: Europe, Asia

---

## Tools

`Python` `pandas` `NumPy` `matplotlib` `seaborn` `Google Colab`

---

## Key Findings

**Categories**  
Cosmetics generate the highest profit margin. High-volume categories (Household, Office Supplies) operate on lower margins — scale is their revenue driver, not efficiency.

**Countries**  
San Marino and Andorra show the highest profit efficiency. Ukraine and Andorra have high costs relative to volume — cost optimization is needed.

**Sales Channels**  
Online and Offline channels contribute comparably. Both should be supported in parallel rather than prioritizing one.

**Delivery**  
Slowest deliveries occur in the most profitable categories (Cosmetics, Office Supplies, Baby Food). Hungary and Slovakia show extreme delays — up to 50 days. Profit does not correlate with delivery speed, so logistics improvements can be made purely for customer experience without revenue risk.

**Seasonality**  
Clear weekly patterns: Cereal, Clothes, Baby Food peak on weekends. Cosmetics peak on Fridays. August is consistently the weakest month — inventory and promotions should be planned accordingly.

---

## Business Recommendation

- Scale Cosmetics — highest margin category with growth potential
- Fix logistics in Hungary and Slovakia — extreme delays without profit impact
- Plan promotions before August to smooth seasonal revenue dips
- Stabilize Europe revenue through seasonal forecasting

---

## Files

| File | Description |
|------|-------------|
| `sales_data_analysis.ipynb` | Full analysis notebook |
