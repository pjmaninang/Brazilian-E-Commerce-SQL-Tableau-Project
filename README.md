![banner](https://github.com/pjmaninang/Brazilian-E-Commerce-SQL-Tableau-Project/blob/main/banner.jpg?raw=true)
# E-Commerce Sales and Product Performance Analysis
## Project Overview

This synthetic Brazilian e-commerce company requested a sales analysis for the period of September 2016 to September 2018. Its SQL database contains extensive information on sales, products, sellers, and order reviews. This project conducts a comprehensive analysis and visualization of the sales data to uncover key insights that can inform the company’s strategic planning.

To provide a thorough sales and product performance analysis, insights and recommendations were focused around:

- **Sales Trends Analysis:** Evaluating the company's sales patterns across the country, with KPIs centered around revenue, order volume, and average order value (AOV)
- **Product Performance:** Analyzing the sales data to uncover the company's top and bottom performing products in regards to the key KPIs
- **State Comparisons:** Evaluating customer distribution and sales volumes across different states in Brazil

The original dataset can be found and downloaded [here](https://www.kaggle.com/datasets/terencicp/e-commerce-dataset-by-olist-as-an-sqlite-database/data)

An interactive Tableau dashboard can be viewed and downloaded [here](https://public.tableau.com/app/profile/pj.maninang/viz/BrazilEcommerceDashboard_17545320710820/Dashboard1)

The SQL queries utilized to prepare the data for the dashboard can be found [here](https://github.com/pjmaninang/Brazilian-E-Commerce-SQL-Tableau-Project/blob/main/ecommerce_sql_script.sqbpro)

## Data Structure

The company's database structure consists of these 11 tables:

![Database Schema](https://github.com/pjmaninang/Brazilian-E-Commerce-SQL-Tableau-Project/blob/main/Database%20Schema.png?raw=true)

## Executive Summary

### Overview of Findings

From October 2016 to November 2017, revenue rose from $20K to a peak of $438K, maintaining over $340K for the final seven months, reflecting strong sales scaling and stable demand. Monthly revenue patterns show sharp fluctuations, including a 56.9% surge in November 2017 followed by a 33.9% drop in the next month. Sales are concentrated in five high-performing categories—bed_bath_table, health_beauty, computers_accessories, furniture_decor, and watches_gifts—with São Paulo generating nearly half of total revenue and orders. In contrast, low-penetration states like Roraima, Amapá, and Acre present opportunities for targeted marketing and distribution expansion.

Below is the dashboard's general overview without any filtering, but the complete interactive dashboard can be found and downloaded [here](https://public.tableau.com/app/profile/pj.maninang/viz/BrazilEcommerceDashboard_17545320710820/Dashboard1)
![Dashboard](https://github.com/pjmaninang/Brazilian-E-Commerce-SQL-Tableau-Project/blob/main/Dashboard.png?raw=true)

## Findings and Insights

### Sales Trends

- Overall revenue grew substantially from $20K in October 2016 to a peak of $438K in November 2017, maintaining levels above $340K for the final seven months of available data. This sustained high performance in the latter period indicates a successful scaling of sales operations and a strong, stable customer demand base.
- Revenue trends show sharp month-over-month changes, with the most notable peak growth from Oct 2017 to Nov 2017 (56.9%), and an immediate significant revenue loss of 33.9% in Dec 2017. This can indicate possible promotional periods or seasonal demand spikes of their products
- Despite generating $20K in revenue from 309 orders in October 2016, there were no recorded sales in November and only a single order in December, suggesting a potential operational disruption or data reporting gap during this period
- Average order value remains stable at approximately $50 per order across the entire dataset timeline, indicating consistent customer spending behavior and pricing stability

### Product Performance

- The top five product categories—bed_bath_table, health_beauty, computers_accessories, furniture_decor, and watches_gifts—each generate over $400K in revenue and more than 5,000 total orders. This concentration of sales highlights a core set of high-demand categories that are critical to sustaining overall revenue performance
- Among the top 10 performing product categories, watches/gifts ($71.16), garden tools ($66.72), and computers/accessories ($66.36) hold the highest average order values. This suggests that these categories attract higher-value purchases, making them key drivers for maximizing revenue per transaction
- Several product categories, such as security_and_services ($91) and fashion_childrens_clothes ($220), and cds_dvds_musicals($336) generate negligible revenue, indicating either minimal demand or potential issues with product visibility and availability

### State Comparisons

- São Paulo is the clear leader in sales performance, generating $2.1 million in revenue from 41,106 orders—accounting for nearly half of both total revenue and total order volume. This dominance underscores the state’s critical role in the company’s market presence and highlights it as a key region for sustaining growth and implementing targeted retention strategies
- The three states with the smallest customer bases—Roraima (44), Amapá (68), and Acre (80)—consistently generate minimal revenue across the sales periods. Their low customer penetration and limited sales contribution suggest untapped market potential that may require targeted marketing, localized outreach, or improved distribution channels to stimulate growth

## Recommendations

- Implement retention programs and exclusive offers in São Paulo to sustain its nearly 50% contribution to revenue, while replicating successful strategies in other high-potential regions
- Develop targeted campaigns to mitigate sharp post-promotion or seasonal drops, particularly after peak months like November, to maintain revenue stability
- Launch localized marketing, partnerships, and distribution initiatives in low-penetration states such as Roraima, Amapá, and Acre to capture new customer bases and grow regional sales

## Limitations

- **Incomplete Sales Data for 2016 and 2018:** Sales records for these years are cover only a small portion of the complete year, with September 2018 only having 1 order. This has resulted in understated revenue figures, as well as inaccurate month-over-month percentages for the adjacent months
- **Limited Customer Demographics:** The customers table contains only customer ID and state information, limiting the ability to further aggregate or segment sales trend analysis by additional demographic attributes
