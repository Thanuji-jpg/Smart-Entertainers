# Project PrismCX – Emphasizing customer experience and segmentation across many dimensions.
📊 Project PrismCX: Customer Segmentation for IoT Smart Home Solutions
Project PrismCX is a customer analytics initiative designed to uncover strategic behavioral insights for a smart home automation brand. By integrating RFM segmentation (Recency, Frequency, Monetary) with the CORE framework (Convert, Optimize, Retain, Exit), the project delivers an actionable customer classification model. These insights are visualized through an interactive Tableau dashboard for real-time business decision-making.

# 📁 Dataset Summary
Dataset: SmartHome_PrismCX_Segmentation.csv
Size: 2,200+ transaction records
Includes:

# Customer Attributes: Age group, gender, region

Purchase Behavior: Date, value, and category of IoT device purchased

RFM Metrics: Days since last purchase, number of transactions, total spend

Scored Fields: R, F, M scores using quantile segmentation (1–4 scale)

# Tagging Dimensions:

CustomerType: First-time vs. returning customers

Top_Spender: High-expenditure customers

IsLoyalCustomer: Based on frequency and recency

Churn_Risk: Customers showing signs of disengagement

CORE_Segment: Final category - Convert, Optimize, Retain, or Exit

# 🛠 Tools & Technologies
Tool	Purpose
Python (pandas)	Data preparation, feature generation, and scoring logic
Tableau	Visual analytics and dashboard creation
GitHub	Documentation and version control

# ✅ Key Steps Performed
Data Preparation:

Cleaned and normalized smart device transaction data

Derived Recency, Frequency, and Monetary values per customer

# Scoring & Tagging:

Assigned RFM scores using quantile binning

# Labeled key customer traits:

New vs. Repeat Buyer

High Spender Tag (Top Quartile)

Loyalty Identifier

Inactivity & Churn Risk

# Categorized each customer into segments:

Convert: New or low-engagement customers

Optimize: Moderate spenders with growth potential

Retain: High-value and frequent buyers

Exit: At-risk customers with minimal interaction

# 📈 Tableau Dashboard Features
A centralized dashboard built in Tableau delivers full visibility into customer dynamics:

# 🧮 KPI Tiles
Total Customers

Average Spend per Customer

Churn Rate

Loyalty Percentage

# 📊 Visual Components
CORE Segment Distribution (Bar/Pie chart)

CustomerType Breakdown by Age Group and Region

Churn Risk Overview

RFM Heatmap: Recency vs. Frequency

# 🔍 Dashboard Filters
CORE Segment

Customer Type

Region

Age Group

Gender

Churn Risk

All dashboard elements are interlinked to support dynamic filtering and in-depth exploration.

# 💡 Business Value
Project PrismCX empowers smart home solution providers to:

Target marketing campaigns based on customer lifecycle

Anticipate churn and prioritize engagement

Upsell or cross-sell based on spending patterns

Improve long-term customer retention strategies

# 📌 Final Thoughts
By combining data-driven segmentation with intuitive visualizations, Project PrismCX bridges technical analytics with real-world strategic decisions—fueling growth for IoT-driven home automation businesses.


