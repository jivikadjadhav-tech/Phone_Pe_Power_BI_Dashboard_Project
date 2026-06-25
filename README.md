📊 PhonePe Transaction Analytics Dashboard – Power BI Project
🚀 Project Overview

This project is a PhonePe Transaction Analytics Dashboard developed in Power BI to analyze transaction performance, user behavior, payment success rates, and service-wise transaction trends.

The dashboard transforms raw transaction data into actionable business insights using Power Query, Data Modeling, and DAX calculations, enabling stakeholders to monitor key performance indicators (KPIs) and make data-driven decisions.

🛠️ Tools & Technologies
Power BI
Power Query
DAX (Data Analysis Expressions)
Data Modeling
Interactive Dashboard Design
Data Visualization
📌 Business Objectives
Monitor overall transaction performance.
Analyze transaction value and volume trends.
Track payment success and failure rates.
Understand user demographics and behavior.
Identify top users contributing to transaction value.
Compare weekday and weekend transaction activity.
Evaluate service-wise transaction contribution.
📊 Dashboard Features
1️⃣ KPI Overview
Total Transactions: 300K
Total Transaction Value: ₹3.47 Billion
Unique Users: 108K
Success Rate: 96%
2️⃣ Transaction Trend Analysis
Monthly transaction volume tracking.
Trend comparison across the year.
Identification of peak transaction periods.
3️⃣ Payment Status Analysis
Successful Transactions
Pending Transactions
Failed Transactions
4️⃣ Age Segment Contribution
User distribution by age groups.
Contribution percentage of each age segment.
5️⃣ Service Transaction Value Analysis
Loans
Insurance
Money Transfer
Recharge Services
6️⃣ Top Users Analysis
Top 5 users based on transaction value.
User contribution comparison.
7️⃣ Weekday vs Weekend Usage
Transaction distribution across weekdays and weekends.
Behavioral analysis of customer activity.
📈 Key Insights
🔹 Weekday Transactions Dominate

Users perform significantly more transactions during weekdays compared to weekends.

🔹 Loan Services Generate Maximum Value

Loan-related transactions contribute the highest share of overall transaction value.

🔹 High Transaction Success Rate

The platform maintains an impressive success rate of 96%, indicating strong operational reliability.

🔹 User Concentration

A small group of users contributes a significant portion of transaction value.

🔹 Consistent Monthly Activity

Transaction volume remains stable with periodic growth spikes throughout the year.

🧮 DAX Measures Used

Examples of key measures created:

Total Transactions = COUNT(Transaction[Transaction_ID])

Total Value = SUM(Transaction[Amount])

Unique Users = DISTINCTCOUNT(Transaction[User_ID])

Success Rate =
DIVIDE(
    CALCULATE(COUNTROWS(Transaction),
    Transaction[Status]="Successful"),
    COUNTROWS(Transaction)
)
🔄 Power Query Transformations
Data Cleaning
Removing Null Values
Data Type Conversion
Creating Custom Columns
Date Transformations
Data Validation
Merging and Appending Data Sources
📂 Data Model

The dashboard follows a structured data model with:

Fact Transactions Table
User Dimension Table
Service Dimension Table
Date Dimension Table

This enables efficient filtering, slicing, and DAX calculations.

🎯 Skills Demonstrated
Business Intelligence Reporting
Data Cleaning & Transformation
Data Modeling
DAX Calculations
KPI Development
Dashboard Design
Data Storytelling
Analytical Thinking
📷 Dashboard Preview

(Insert Dashboard Screenshot Here)

👨‍💻 Author

Jivika D. Jadhav
Aspiring Data Analyst | Power BI | SQL | Excel | Data Visualization

📧 Add your email
🔗 Add your LinkedIn Profile
