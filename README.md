# 🛡️ Shield Insurance Analytics Dashboard

----------------------------------------------------------------------------------------------

# 🔗 Live Dashboard : 👉 **[View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTZhNzhkZjEtMTkyYi00ODQ1LTg4NjctYTVmMGYxNDM4NGNmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

----------------------------------------------------------------------------------------------

# 📊 Project Overview

Shield Insurance is a fictional insurance company used in the Codebasics
Data Analytics Internship. This project demonstrates an
end-to-end Business Intelligence solution built in **Power BI**,
transforming raw insurance data into an interactive dashboard that
enables stakeholders to monitor customer growth, revenue trends, policy
performance, sales channels, and demographic insights.

Unlike a basic dashboard showcase, this repository is structured as a
business case study---from understanding the problem to delivering
actionable recommendations.

------------------------------------------------------------------------

# 📑 Table of Contents

- About the Company
- Business Problem
- Objectives
- Dataset
- Data Model
- Data Cleaning & Transformation
- Data Modeling
- DAX Measures
- Dashboard Features
- Dashboard Walkthrough
- KPIs
- Business Questions Answered
- Key Insights
- Recommendations
- Business Impact
- Challenges
- Learnings
- Tech Stack
- Future Improvements

------------------------------------------------------------------------

# 🏢 About Shield Insurance

Shield Insurance provides comprehensive insurance plans for individuals
and businesses. The company wanted a Proof of Concept dashboard to
evaluate how interactive analytics could support better strategic
decisions before investing in a larger BI implementation.

# 🎯 Business Problem

Management lacked a centralized reporting solution to monitor revenue,
customer acquisition, policy performance, sales modes, and settlements.
Static reports made it difficult to identify trends, compare regions, or
evaluate customer demographics.

The goal was to design an interactive Power BI dashboard that converts
operational data into actionable business insights.

# ✅ Project Objectives

- Monitor Total Revenue and Total Customers
- Track Daily Revenue Growth (DRG)
- Track Daily Customer Growth (DCG)
- Analyze Month-over-Month performance
- Evaluate sales channels
- Analyze age groups
- Compare city performance
- Study policy popularity
- Estimate settlements
- Provide actionable recommendations

# 📂 Dataset

Tables provided: - dim_customer - dim_date - dim_policies - fact_premiums -
fact_settlements

# 🧹 Data Cleaning & Transformation

- Removed unnecessary columns
- Corrected data types
- Split sales mode fields
- Created Age and Age Group columns
- Created calendar attributes
- Cleaned missing values
- Built Power Query transformations

# ⭐ Data Model

> **TODO:** Insert Data Model image here.

# 🧮 Important DAX Measures

- Total Revenue
- Total Customers
- DRG
- DCG
- Previous Month Revenue
- Previous Month Customers
- Revenue Growth %
- Customer Growth %
- Expected Settlement
- Revenue %
- Customer %

# ✨ Dashboard Features

- Interactive slicers
- Dynamic KPI cards
- Navigation buttons
- Tooltips
- Cross-filtering
- Bookmarks
- Dynamic visuals
- Drill interactions
- Professional theme
- Responsive layout

# 🖥️ Dashboard Walkthrough

## 🏠 Home Page

**TODO:** Insert Home Dashboard Screenshot

Description: Landing page providing navigation to all analytical
sections.

------------------------------------------------------------------------

## 📊 Overview Dashboard

**TODO:** Insert Overview Screenshot

Highlights: - Revenue - Customers - DRG - DCG - City analysis - Monthly
trends

------------------------------------------------------------------------

## 📈 Sales Mode Dashboard

**TODO:** Insert Sales Dashboard Screenshot

Highlights: - Offline vs Online - Revenue contribution - Customer
contribution - Monthly trend

------------------------------------------------------------------------

## 👥 Age Group Dashboard

**TODO:** Insert Age Dashboard Screenshot

Highlights: - Settlement analysis - Revenue by age - Customer
distribution - Policy preference

# 📌 Key KPIs

KPI Description
----------------------------------------------
Total Revenue
Total Customers
DRG - Daily Revenue Growth
DCG - Daily Customer Growth
Revenue Growth % Month-over-Month
Customer Growth % Month-over-Month
Expected Settlement
Estimated Claim Value

# ❓ Business Questions Answered

- Which city generated the highest revenue?
- Which city acquired the highest customers?
- Which policy is most popular?
- Which policy generated maximum revenue?
- Which month recorded peak performance?
- Which sales channel performs best?
- Which age group contributes the most?
- Which age group has highest settlement?

# 💡 Key Insights

- **Customer Base:** Shield Insurance serves a total of **26,841 customers**, reflecting a strong and diverse customer portfolio.

- **Revenue Performance:** The company generated an overall revenue of **₹989.3 Million**, demonstrating healthy premium collections during the analysis period.

- **Top Performing City:** **Delhi NCR** emerged as the leading market, contributing **11,007 customers** and generating **₹401.6 Million** in revenue, making it the highest-performing city across all regions.

- **Highest Revenue Age Group:** Customers aged **31–40 years** formed the largest customer segment with **11,455 customers**, contributing approximately **₹356 Million** in premium revenue. This indicates that working professionals represent the company's most valuable customer segment.

- **Monthly Growth Trends:** **March 2023** recorded the strongest business performance, achieving approximately **85% growth in revenue** and **82% growth in customer acquisition** compared to previous months. However, **April 2023** experienced a notable decline of **41.7% in revenue** and **41.4% in customer acquisition**, highlighting the need to investigate seasonal demand fluctuations.

- **Sales Channel Performance:** The **Offline Agent** channel remained the primary contributor, accounting for **55.6% of total revenue** and **55.4% of total customers**, while online channels showed gradual adoption and future growth potential.

- **Revenue Distribution Across Sales Modes:** Revenue contribution across different sales channels remained relatively balanced, ranging between **12.6% and 16.3%**, indicating a well-diversified sales ecosystem.

- **Most Popular Insurance Policy:** **Policy ID – POL4321HEL** attracted the highest customer base with **4,434 policyholders**, making it the company's most preferred insurance product.

- **Highest Revenue Generating Policy:** **Policy ID – POL2005HEL** generated approximately **₹324.3 Million** in premium revenue, making it the highest revenue-contributing policy in the portfolio.

- **Expected Settlement Analysis:** The **31–40 years** age group also recorded the highest expected settlement value, suggesting a combination of high policy adoption and significant claim exposure within this demographic.

# 🚀 Recommendations

1. **Replicate High-Performing Strategies**
   - Analyze the factors behind **March 2023's 85% revenue growth** and replicate successful campaigns, promotions, or customer acquisition strategies during other months.

2. **Strengthen Presence in Delhi NCR**
   - Since **Delhi NCR contributes over ₹401.6 Million in revenue**, continue investing in localized marketing, partnerships, and customer engagement initiatives while replicating successful strategies in other metropolitan cities.

3. **Target the 31–40 Age Segment**
   - The **31–40 age group contributes over ₹356 Million in revenue** and represents the largest customer segment. Introduce personalized insurance products, loyalty benefits, and cross-selling opportunities to maximize customer lifetime value.

4. **Accelerate Digital Sales Channels**
   - Although Offline Agents contribute more than **55% of total revenue**, the gradual growth of online channels indicates strong future potential. Improving the mobile application, website experience, and digital marketing campaigns can significantly increase online customer acquisition.

5. **Empower Offline Agents**
   - Since Offline Agents remain the company's strongest sales channel, invest in continuous training, performance incentives, and digital support tools to sustain their contribution while improving operational efficiency.

6. **Promote High-Performing Policies**
   - Expand marketing efforts around **POL4321HEL** and analyze the success factors behind **POL2005HEL**, using these insights to improve other insurance products and increase overall premium revenue.

7. **Improve Claim & Settlement Planning**
   - As customers aged **31–40 years** have the highest expected settlement value, implementing predictive risk assessment and optimized claim management strategies can improve profitability while maintaining customer satisfaction.

8. **Leverage Data-Driven Personalization**
   - Utilize customer demographics, purchasing behavior, and policy preferences to recommend relevant insurance products, improve retention, and increase cross-selling and upselling opportunities.

9. **Monitor Seasonal Performance**
   - Investigate the sharp **41.7% revenue decline observed in April** to identify seasonal trends and introduce proactive campaigns that stabilize revenue throughout the year.

# 📈 Business Impact

The dashboard enables stakeholders to:

- Monitor KPIs in real time
- Identify high-performing markets
- Improve customer targeting
- Optimize policy portfolio
- Strengthen sales strategy
- Support data-driven decision making

# ⚠️ Challenges Faced

- Building an optimized star schema
- Writing reusable DAX measures
- Month-over-month calculations
- Interactive navigation
- Designing intuitive visuals
- Performance optimization

# 📚 Learnings

- Power Query
- Data Modeling
- DAX
- KPI Design
- Dashboard Storytelling
- Business Analytics
- Interactive Reporting
- Power BI Report feature Implementation and Best Practices

# 🛠️ Tech Stack

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- PowerPoint
- Git & GitHub

# 🔮 Future Improvements

- Row-Level Security
- Mobile Layout
- Paginated Report
- Forecasting
- AI Custom Visuals
- Incremental Refresh
- Power BI Service Alerts

------------------------------------------------------------------------

## ⭐ If you found this project useful, consider giving the repository a Star.

Made with ❤️ using Power BI, DAX, Power Query, and Excel.
