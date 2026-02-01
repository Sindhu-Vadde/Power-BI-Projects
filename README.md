**📊 Retail Sales Analytics Dashboard (Power BI)**

This project showcases a comprehensive Retail Sales Analytics Dashboard developed using the Large Retail Dataset from Kaggle. The dashboard is designed to deliver both high-level business insights and advanced analytical intelligence, while allowing users to dynamically explore trends at daily, weekly, and monthly levels through an interactive timeframe selection.

The dashboard is divided into two analytical layers:

🟢 Page 1: Basic Analytics
(Descriptive & Operational Insights)


🔵 Page 2 – Advanced Analytics


**🟢 Page 1: Basic Analytics**

This page focuses on core KPIs and summary insights that provide an immediate view of business performance across multiple time granularities.

**📌 Key KPIs**

💰 Total Sales – Overall revenue generated

👥 Total Customers – Unique customers served

🧾 Total Transactions – Number of completed purchases

🛒 Average Order Value (AOV) – Average spend per transaction

🔁 Repeat Customer Rate – Customer retention indicator

⚠️ Churn Rate – Percentage of customers who did not return

📅 All KPIs and visuals on this page dynamically adjust between Daily, Weekly, and Monthly views based on the selected timeframe parameter.

**👤 Customer Overview**

This section analyzes customer behavior and demographics across different time granularities:

Customer distribution by income bracket, education level, gender, marital status, and occupation

Engagement analysis using app usage, social media engagement, and email subscriptions

Trend analysis that dynamically switches between daily, weekly, and monthly views

**📦 Product Overview**

Provides product-level insights with flexible time resolution:

Sales contribution by product category

Units sold distribution across categories

Identification of consistently high- and low-performing product groups over different timeframes

**🧮 Sales Overview**

Examines sales patterns with interactive timeframe control:

Sales trends across daily, weekly, and monthly views

Sales distribution by payment method

Impact of promotion type, promotion channel, and target audience

Seasonal and short-term demand effects visible through timeframe switching

**🔵 Page 2: Advanced Analytics
(Strategic & Diagnostic Insights)**

The second page introduces advanced analytical metrics that provide deeper insights into efficiency, dependency, and concentration, while still supporting multi-granular time analysis.

🧠 Advanced Customer Analytics

💵 Average Revenue per Customer

🔢 Average Transactions per Customer

Customer value concentration analysis across income and occupation segments

Retention and repeat purchase behavior analyzed at daily, weekly, and monthly levels

🧩 Advanced Product Analytics

📈 Daily Active SKUs Sold with dynamic aggregation for weekly and monthly views

Product category stability and volatility analysis

Identification of products driving sustained versus short-term sales spikes

💡 Advanced Sales Analytics

🎯 Top-N Products Sales Share % – Measures revenue concentration risk

🔀 Sales Value Bridge (Waterfall Analysis) – Explains transitions from gross to net sales

💸 Discount Intensity Analysis – Tracks pricing pressure across different timeframes

📣 Promo Sales Share by Promotion Channel – Evaluates promotion dependency

📍 Sales Share by Distance Band – Analyzes customer proximity impact on revenue

📦 Data Scale & Performance Considerations

This dashboard was built on a large-scale retail dataset, closely reflecting real-world production analytics scenarios.

**📊 Dataset Characteristics**

📈 1+ million records

🧩 50+ columns spanning customers, transactions, products, promotions, and geography

🔧 Data Handling & Optimization

⚙️ Designed an efficient data model to support high-cardinality dimensions

🧠 Implemented optimized, context-aware DAX measures that adapt correctly across daily, weekly, and monthly views

📊 Used appropriate aggregation levels to ensure smooth performance during timeframe switching

🚀 Maintained dashboard responsiveness despite dataset size and analytical complexity

**🛠 Tools & Technologies**

🧩 Power BI – Interactive data modeling and visualization

📐 DAX – Advanced calculations with dynamic time-context handling

📊 Kaggle Retail Dataset – Large-scale retail transactional data

**🎯 Key Takeaways**

✅ Supports dynamic Daily / Weekly / Monthly analysis

✅ Demonstrates advanced DAX and context management

✅ Handles large datasets efficiently

✅ Built for real-world retail decision-making
