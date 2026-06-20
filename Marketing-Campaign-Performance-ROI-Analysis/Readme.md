# Marketing-Campaign-Performance-ROI-Analysis | Tools: SQL & BI
Analyzed 55,000+ Nykaa marketing campaigns to figure out which channels, campaign types, and customer segments actually drive ROI.
Done using MySQL for analysis and Power BI for visualization.

---

## What's in this repo
- nykaa_campaign_data.csv — raw campaign data (55,555 rows)
- marketing_campaign_roi_analysis.sql — all SQL queries
- marketing_analysis.pbix — Power BI dashboard

---

## What the SQL covers
- ROI ranking across all campaigns
- Best performing campaign per channel
- Revenue vs cost efficiency by channel
- Full conversion funnel (Impressions → Clicks → Leads → Conversions)
- CTR and lead conversion rates
- Monthly revenue trends
- Month-over-month ROI comparison using LAG
- Customer segment breakdown

---

## Tools Used
- MySQL 8.0 — window functions, CTEs, subqueries, time series
- Power BI Desktop — interactive dashboard
- CSV — raw data source

---
## Dashboard 
<img width="1264" height="724" alt="image" src="https://github.com/user-attachments/assets/d2837862-9008-4d10-9959-78edf503565b" />
--
<img width="1267" height="733" alt="image" src="https://github.com/user-attachments/assets/8b5df920-78d3-469e-9a8f-1639c9efabbf" />
--
<img width="1266" height="732" alt="image" src="https://github.com/user-attachments/assets/a1c43dd5-bdcf-481b-aef1-cf9dedd3ae03" />
--

## Key Insights
- Channel Efficiency
-- Email has the best revenue-to-cost ratio (1,389x), followed by Instagram (1,379x) and WhatsApp (1,370x). Facebook is the least efficient. The difference between channels is small overall — the bigger wins come at the individual campaign level.
- Campaign Type ROI
-- All five types perform closely (avg ROI 2.68–2.75). Social Media leads marginally, but no single type dramatically outperforms the rest. The real outliers are specific campaigns, not types.
- Customer Segments
-- Working Women drive the highest avg ROI (2.77) and highest avg revenue per campaign (₹5.22L). Youth is the weakest segment on both. Tier 2 City Customers punch above expectations on revenue despite lower ROI.
- Conversion Funnel
-- Influencer campaigns have the best CTR (8.55%) and lead-to-conversion rate (55.2%). Email has a lower CTR but converts leads almost as well — it attracts fewer clicks but the intent is higher.
- Top Campaigns
-- The single best campaign (NY-CMP-13007) was a Paid Ads campaign running across Email + YouTube + Facebook with an ROI of 74.42 — about 27x the dataset average. Four of the top 5 campaigns by ROI are Paid Ads running on multiple channels simultaneously.
- Revenue Trend
-- Peak revenue was July 2024 (₹263 Cr). Dips in September 2024 and February 2025. June 2025 shows low numbers but is an incomplete month in the data.

---

