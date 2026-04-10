# Global Retail Sales Performance Dashboard

**Power BI | RFM Analysis | Business Insights & Actionable Recommendations**

[Sales Dashboard Overview](link)

### Executive Summary
This Power BI dashboard analyzes **$55.76M** in global retail sales data for a multi-national company specializing in electronics, home appliances, cameras, cell phones, and entertainment products.  

Although total revenue and profit reached **$55.76M** and **$32.66M** respectively, the business faced a **severe revenue decline of -75.81%** after peaking in 2019. Through in-depth analysis and RFM customer segmentation, I identified critical business problems: over-dependence on a few product categories, colors, offline channels, and the U.S. market, combined with high customer churn.  

This project delivers **clear, actionable recommendations** to recover revenue growth, improve customer retention, and reduce business risk.

---

### Business Context & Situation
The company operates across multiple continents with both **offline stores** (79.55% of revenue) and **online channels**. It sells thousands of products under various brands (Adventure Works, Contoso, Fabrikam, etc.).  

In recent years, the business experienced significant revenue drop after 2019, raising concerns about sustainability and long-term profitability.

---

### Problem Statement
**Core business problems identified:**
- Revenue declined sharply after 2019 (peak $5.8M in Q4 2019 → dropped to $1.0M in 2020).
- Heavy dependency on **Computers** category and **Black** color.
- Over-reliance on **United States** market and **Offline** stores.
- High customer churn: large portions of customers fall into “At Risk”, “Hibernating”, and “Lost” segments according to RFM analysis.
- Unstable retention rate across months and years.

These issues risk continued revenue loss and reduced market competitiveness if not addressed.

---

### Data & Methodology
- **Dataset**: Global retail sales transactions (2016–2021) with product, customer, store, and order details.
- **Data Modeling**: Star schema with fact table (`fact_Sales`) and multiple dimension tables + custom RFM tables.
- **Key Techniques**:
  - RFM (Recency, Frequency, Monetary) customer segmentation
  - Time intelligence (YoY, QoQ, MoM)
  - Dynamic measures and parameters in DAX
  - Advanced visualizations (scatter plot, heatmap, gauge, treemap)

**Tools**: Power BI Desktop, DAX, Power Query.

---

### Key Insights
1. **Revenue Decline Post-2019**: Sharp drop after 2019 peak, with 2020 and 2021 showing significantly lower performance.
2. **Category & Color Concentration**: Computers category dominates revenue; Black color alone contributes the highest sales.
3. **Channel & Market Dependency**: Offline stores generate 79.55% of revenue; United States accounts for the largest share.
4. **Customer Churn Risk**: RFM analysis reveals high proportion of “At Risk”, “Hibernating”, and “Lost” customers.
5. **Store Performance Variation**: Revenue does not always correlate linearly with store size or age.

---

### Recommendations & Action Plan
**1. Customer Retention & Reactivation**  
→ Launch targeted re-engagement campaigns for “At Risk” and “Hibernating” segments.  
→ Offer loyalty programs and personalized discounts for “Champions” and “Loyal” customers to increase repeat purchase rate.

**2. Channel Expansion**  
→ Accelerate online sales growth (currently only 20.45%) through digital marketing and e-commerce optimization to reduce dependency on offline stores.

**3. Product Portfolio Diversification**  
→ Reduce reliance on Computers and Black color by promoting underperforming but high-potential categories (Home Appliances, Cameras & Camcorders).  
→ Introduce new colors and bundle offers to balance revenue distribution.

**4. Market & Store Optimization**  
→ Expand presence in high-potential markets (United Kingdom, Germany, Canada).  
→ Review and optimize store locations: close or reposition underperforming large stores based on revenue-per-square-meter analysis.

**5. Pricing & Profitability Control**  
→ Closely monitor Cost-to-Price ratio and avoid excessive discounting on low-margin products.

---

### Business Impact (Expected)
- **Short-term**: +15–20% revenue recovery within 6–12 months through customer reactivation and online expansion.
- **Medium-term**: Improve customer retention rate by 10–15% and reduce churn.
- **Long-term**: More balanced revenue mix across categories, channels, and geographies → lower business risk and sustainable growth.

---

### Challenges & Learnings
**Challenges**:
- Identifying the real business problem from raw data (not just creating beautiful charts).
- Complex data model with many tables and the need to build custom RFM logic from scratch.
- Translating technical insights (RFM scores, YoY trends) into clear, actionable business recommendations that non-technical stakeholders can understand and implement.

**Learnings**:
- Business context is more important than visualization. The ability to **identify problems** and turn data into **specific recommendations** is what creates real value.
- RFM analysis is a powerful framework to drive customer strategy.
- Clear storytelling and business-oriented communication are key skills for a Data Analyst.

---

### Tech Stack
- **Visualization**: Power BI Desktop
- **Modeling & DAX**: Advanced DAX, Time Intelligence, Dynamic Parameters
- **Data Transformation**: Power Query
- **Analysis**: RFM Segmentation
- **Version Control**: GitHub

---

**Project completed in 2026**  
Feel free to reach out if you want to discuss the analysis or collaborate!
