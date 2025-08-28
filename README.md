# Power BI Sales Dashboard

## Interactive Revenue & Profit Analysis Across Indian Markets and Customers

This project showcases an interactive **Power BI dashboard** that analyzes sales performance, profitability, and customer insights across multiple Indian markets.  
The dashboard provides decision-makers with a comprehensive view of revenue contributions, profit margins, customer performance, and sales trends from 2017–2020. Report includes dropdown filters for **Fisical Year and Year** allow users to dynamically explore trends across different time periods.

---

## 💰 Profit Insights
Differentiating markets by **Revenue, Profit Contribution, and Profit Margin** profitability by market and customer is visualized to identify high- and low-margin areas.  

![Profit Analysis](https://github.com/Ten-Son7/PowerBISalesInsight/blob/main/Profit%20Analysis.png)  

- While **Delhi** had the highest **Revenue Contribution** and contribution to **Profits**, **Surat** had the highest Profit margin at **4.9%** while **Delhi** had a profit margin of **2.3%**.
- Some markets (e.g., **Bengaluru**) negatively impact profitability (**-20.8%**)  

---

## 💪 Performance Insights
As the name suggests, this dashboard analyzes the performance of the company. Report includes a drill-through analysis for comparing **Profit Margins** across zones, markets, customers, and products.

![Performance Analysis](https://github.com/Ten-Son7/PowerBISalesInsight/blob/main/Performance%20Insights.png)  

- **1st drill-through** shows profit margin of each zone: North, Central, South. **2nd drill-through** shows the profit margin of each markets. **3rd drill-through** shows profit margin of each customers. **4th drill-through** shows the profit margin of each product.
- Unlike the profit analysis, using the **Profit Target** slicer, we can judge the performance of each drill-through category by setting a profit goal.
- The **Revenue Trend** graph is also different as it compares last year's revenue to the next when focusing on the bar graph. The line graph shows an interesting relationship between **revenue** and **profit**, where starting july 2018 as **profit margin increased, revenue decreased**.

---

## 📊 Key Insights
The dashboard highlights **overall revenue performance** and **top contributing markets**.

![Key Insights](https://github.com/Ten-Son7/PowerBISalesInsight/blob/main/Key%20Insights.png)  

- Total Revenue: ₹985M  
- Delhi NCR and Mumbai contribute **~68%** of overall sales  
- Revenue trend shows the growth as well as the decline of revenue. It alights similarly with the decline of product sales.

---

## 🛠 Known Issues
- **Revenue Trend**: Difficult to assess the state of the company with only four years of data.
- **Blank product entries**: Some transactions have missing product details (shown as `(Blank)` in visuals) becuase **product_code** greater than **Prod279** are referencing products that don't exist in the prodcut table.  
