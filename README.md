# 📊 Bank Telemarketing Success Campaign Analysis
Power BI | Customer Analytics | Campaign Performance | Conversion Analysis

## 🎯 Project Overview
This project analyzes the performance of a bank's telemarketing campaign to understand which customer characteristics, campaign interactions, contact strategies, and historical engagement patterns are associated with successful subscription outcomes.

The analysis was developed as a Power BI business intelligence solution, transforming customer and campaign-level data into an interactive analytical dashboard.

The project focuses on moving beyond simple campaign reporting to answer a more important business question:

**What customer and campaign characteristics are associated with higher conversion, and how can these insights support more targeted campaign decisions?**

The analysis examines:

- Customer demographics
- Customer financial and product-related characteristics
- Campaign contact history
- Communication channels
- Contact timing
- Number of campaign contacts
- Previous campaign outcomes
- Subscription outcomes
- Customer segments
- Conversion performance
- Campaign effectiveness

The final dashboard provides a consolidated view of campaign performance and customer behavior, allowing users to explore conversion patterns across different customer and campaign dimensions.

---

## 📈 Dashboard Preview
<img width="1800" height="1200" alt="Bank Telemarketing Mockup" src="https://github.com/user-attachments/assets/eb66db6b-2aa3-41cf-a5f7-6583557acb1f" />

---

## ⚠️ Problem Statement

Bank telemarketing campaigns involve significant operational effort because each campaign requires customer selection, contact attempts, agent time, communication resources, and follow-up activity.

However, campaign performance can vary considerably across customer groups and contact strategies.

Without structured analysis, it becomes difficult to determine:

- Which customer groups convert more frequently
- Which communication channels perform better
- Whether repeated contact is associated with improved or reduced conversion
- How previous campaign outcomes relate to current results
- Which customer characteristics are associated with subscription
- Where campaign resources may be concentrated
- Which segments require different engagement strategies

The objective of this project was therefore to transform campaign data into a decision-support solution that provides visibility into customer behavior, campaign performance, and conversion drivers.


## 🎯 Project Objectives

Banks often run telemarketing campaigns to promote term deposits, but conversion rates are typically low.  
This project aims to answer:
- What factors influence a customer’s likelihood to subscribe?
- Which customer demographics are most responsive to campaigns?
- How can marketing strategies be optimized to improve conversion rates?
- Overall campaign conversion performance.
- Customer characteristics associated with subscription outcomes.
- Campaign performance across customer segments.
- The relationship between contact strategy and conversion.
- Communication channels and their associated outcomes.
- The influence of previous campaign outcomes.
- Patterns associated with successful conversions.
- Then build an interactive Power BI dashboard for campaign monitoring.
- Translate analytical findings into actionable targeting and campaign recommendations.
  
---
## 🧠 Key Business Questions

The analysis was designed around the following questions:

**Campaign Performance**
- What is the overall campaign conversion rate?
- How many customers subscribed versus did not subscribe?
- How does campaign performance vary across customer groups?
- Which campaign characteristics are associated with stronger conversion performance?

**Customer Analysis**
- Which customer segments show higher subscription rates?
- How does customer demographic composition vary by campaign outcome?
- Are there observable differences between customers who subscribed and those who did not?
- Which customer characteristics appear most relevant to campaign performance?

**Contact Strategy**
- How does the communication channel relate to conversion?
- Does the number of campaign contacts differ between successful and unsuccessful outcomes?
- How does contact timing relate to campaign performance?
- Are repeated contacts associated with different conversion patterns?

**Historical Engagement**
- How do previous campaign outcomes relate to current subscription behavior?
- Does previous campaign engagement provide useful context for targeting?
- Which historical customer groups demonstrate stronger conversion patterns?
  
**Decision Support**
- Which customer groups may warrant differentiated campaign strategies?
- Where are there opportunities to improve campaign targeting?
- How can campaign performance be monitored more effectively?

## 🔄 Analytical Approach

The project follows a structured business analytics workflow:


Raw Campaign Data

        ↓
        
Data Profiling

        ↓
        
Data Cleaning & Validation

        ↓
        
Exploratory Analysis

        ↓
        
KPI Development

        ↓
        
Customer & Campaign Analysis

        ↓
        
Conversion Analysis

        ↓
        
Segmentation

        ↓
        
Power BI Data Model

        ↓
        
Interactive Dashboard

        ↓
        
Business Insights

        ↓
        
Targeting & Campaign Recommendations

The analysis combines descriptive analytics with comparative customer and campaign analysis.

## 📂 Dataset

The dataset contains customer-level and campaign interaction information used to evaluate telemarketing outcomes.

The analytical structure includes information relating to:
- Customer characteristics
- Financial/customer attributes
- Existing product relationships
- Campaign contact details
- Communication channels
- Contact timing
- Campaign contact frequency
- Historical campaign activity
- Previous campaign outcomes
- Final subscription outcome

**Target Variable**
The primary outcome variable represents whether the customer successfully subscribed to the promoted banking product.
The target is treated as a binary campaign outcome:

Successful Subscription
vs.
No Subscription

Update the exact target field name here to match the dataset used in the project.

**Data Preparation**
Before analysis, the dataset was prepared for reliable reporting and visualization.
The preparation process focused on:
- Data Structure
- Reviewing available fields
- Understanding variable types
- Identifying categorical and numerical variables
- Establishing the analytical grain of the dataset
  
**Data Quality**
- Checking missing values
- Reviewing duplicate records
- Validating categorical values
- Checking numerical fields for unexpected values
- Reviewing date and campaign-related fields
- Ensuring consistent representations of campaign outcomes

**Transformation**
Data was transformed into an analysis-ready structure suitable for Power BI reporting and KPI calculations.

**Analytical Framework**
The project evaluates campaign success across four major analytical dimensions.

**Customer Profile**
Customer characteristics provide context for understanding differences in campaign outcomes.

Examples include:
- Demographic characteristics
- Employment characteristics
- Financial characteristics
- Existing banking relationships
- Loan/product indicators

The purpose is not to assume that a customer characteristic causes conversion, but to identify observable differences in campaign outcomes across customer groups.

**Campaign Interaction**
Campaign variables capture how customers were contacted.
The analysis considers:
- Number of contacts
- Contact channel
- Contact timing
- Duration of interaction
- Current campaign activity

These variables help evaluate how campaign execution relates to observed outcomes.

**Historical Campaign Engagement**
Previous campaign information provides additional behavioral context.
The analysis examines:
- Previous campaign contact
- Previous campaign outcome
- Historical engagement patterns
- Relationship between previous outcomes and current subscription

This provides a way to distinguish customers with different levels of historical campaign engagement.

**Subscription Outcome**
The final outcome is whether the customer subscribed to the promoted product.
This enables calculation of:
- Conversion rate
- Subscription count
- Non-subscription count
- Segment-level conversion
- Channel-level conversion
- Campaign-level conversion

## Key Performance Indicators

The dashboard tracks campaign performance using core KPIs.

| KPI | Definition | Business Meaning |
|---|---|---|
| Total Customers | Number of customers included in the campaign analysis | Campaign population |
| Successful Subscriptions | Number of customers who subscribed | Campaign conversions |
| Non-Subscriptions | Number of customers who did not subscribe | Unconverted campaign population |
| Conversion Rate | Successful subscriptions ÷ total customers | Overall campaign effectiveness |
| Contact Volume | Number of campaign interactions/contacts | Campaign activity |
| Average Contacts | Average number of contacts per customer | Contact intensity |
| Conversion by Channel | Subscription rate by communication channel | Channel performance |
| Conversion by Segment | Subscription rate across customer groups | Targeting performance |
| Previous Campaign Success Rate | Conversion performance among customers with prior campaign outcomes | Historical engagement effectiveness |

Exact measure names and formulas should match the final Power BI model.

**Customer Segmentation**
Customer segmentation is used to compare campaign outcomes across meaningful customer groups.
The segmentation framework considers relevant customer characteristics and campaign behavior to identify groups with different observed conversion patterns.

**The purpose of segmentation is to answer:**
Which customer groups demonstrate different campaign response patterns?
Rather than treating the entire customer population as homogeneous, the analysis evaluates performance across distinct customer profiles.

**Campaign Performance Analysis**
Campaign performance is evaluated across multiple dimensions rather than through a single conversion metric.
- Dimensions analyzed
- Overall campaign outcome
- Customer segment
- Communication channel
- Contact frequency
- Contact timing
- Previous campaign outcome
- Customer characteristics

This allows campaign performance to be decomposed into smaller analytical components.

For example:

Overall Conversion
        ↓
Customer Segment
        ↓
Contact Channel
        ↓
Contact Frequency
        ↓
Historical Campaign Outcome

This layered approach helps identify where conversion differences occur within the customer population.

---

## 🛠 Tools Used
- Power BI  
- Power Query (Data Cleaning & Transformation)  
- DAX (Calculated Measures & KPIs)  

---

## 📊 Key Insights
🔹 Conversion rate improved to 11.3% (vs 3.3%), but still has room for optimization
🔹 Customers aged 26–45 showed the highest response to campaigns
🔹 Admin, technician, and blue-collar jobs recorded the strongest conversions
🔹 First contact was most effective, with diminishing returns from repeated calls

---
## 💡Recommendations:
- Target high-performing customer segments for better ROI 
- Optimize first-contact strategy with better scripts and personalization
- Limit contacts to 2-3 attempts to avoid diminishing returns
- Focus on more effective channels (e.g. cellular/digital)
- Align campaign with high-performing periods and favorable economic conditions
- Use data-driven rules to optimize contact frequency and timing

---

## 🚀 Conclusion
This analysis identifies key drivers of customer conversion in bank telemarketing campaigns. Although conversion improved to 11.3%, better targeting and optimized contact strategies can further improve conversion rates, marketing efficiency and overall ROI.

---

## 👤 Author
**Nkechi Nwachukwu Business Analyst | Data & Operations Analytics**

Portfolio: https://dorothy-data-portfolio.lovable.app

GitHub: https://github.com/nkechi-nwachukwu

LinkedIn: https://linkedin.com/in/nkechi-nwachukwu-82ba911bb
