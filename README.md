# marketing-campaign-performance-analysis
This repository contains an in-depth analysis of marketing campaigns run on Facebook, Instagram, and Pinterest. Using metrics like impressions, clicks, conversions, and engagement, it uncovers insights to evaluate performance, optimize ad spend, and improve future marketing strategies.


## **Table of Contents**
  - [Overview](#overview)

  - [Problem Statement](#problem-statement)

  - [Tools and Methodology](#tools-and-methodology)

  - [Dashboard](#dashboard)

  - [Link to Dashboard](#link-to-dashboard)

  - [Business Questions and Answers](#business-questions-and-answers)

  - [Recommendations](#recommendations)

  - [Conclusion](#conclusion)





## Overview
Our company has been executing a series of dynamic marketing campaigns across popular social media channels; Facebook, Instagram, and Pinterest to promote our products. We have gathered comprehensive daily data for 2023 capturing essential performance metrics such as impressions, clicks, ad spend, conversions, and engagements (including likes, shares, and comments). This project is designed to transform that rich dataset into actionable insights, driving more effective ad spend allocation and refining future marketing strategies.



## <a name="problem-statement"></a>Problem Statement
Executive leadership, marketing directors, and financial controllers require a comprehensive analysis of our multi-channel campaigns. 
This analysis will evaluate key performance metrics;impressions, clicks, conversions, CPC, CTR, and ROI—to identify our top-performing campaigns and platforms. Additionally, it will consolidate insights on geographical engagement, device performance, and ad-level effectiveness, as well as reveal any spend-to-conversion correlations and time-based trends. The goal is to provide clear, actionable recommendations that support strategic decision-making across all levels of the organization, from high-level executive planning to tactical marketing optimization.



## <a name="tools-and-methodology"></a>Tools and Methodology
- ## Tools
  -  MS Powerpoint: I developed the initial wireframe and visual layout for the dashboard to guide design and functionality decisions.

  -  Power Query: I imported the complete dataset, including all columns, into a single table. I transformed the raw dataset into a star schema by splitting it into multiple related tables, which improved performance and manageability. I performed key data transformations, such as joining tables and executing necessary calculations.
    
  -  PowerBI: I utilized DAX formulas to calculate essential performance measures like CPC, CTR, and ROI. I created interactive charts and visualizations to represent the analytical findings. I integrated all visuals and metrics into a cohesive, interactive dashboard.

- ## Methodology
  -  Data Preparation: I loaded the complete dataset into Power Query, ensuring all columns were available for analysis. I restructured the dataset into a star schema by breaking the main table into a central fact table and related dimension tables. I established clear relationships between these tables to optimize query performance and maintain data integrity.

  -  Data Cleaning & Transformation: I identified inconsistencies in the date formats and corrected these by splitting and merging date columns to create a uniform format. I conducted thorough data validation, cross-checking data points and calculated metrics against expected business outcomes. I addressed any anomalies or missing values to ensure the dataset was reliable for further analysis. I executed preliminary calculations during the data preparation phase, ensuring computed fields were correctly reflected across the star schema.

  -  Calculation & Analysis: I leveraged DAX to compute advanced metrics, such as CPC, CTR, and ROI. I created both calculated columns and measures to enable dynamic and interactive data analysis. I continuously validated the computed metrics to ensure accuracy and consistency across all visualizations.

  -  Visualization & Reporting: I designed a 3 page interactive dashboard layout in PowerBI to provide an intuitive user interface for stakeholders.



## <a name="dashboard"></a>Dashboard
### Cover Page
-  ![Image](https://github.com/user-attachments/assets/b9001322-f68e-48ad-ba9c-5f10352a01db)

### Campaign KPIs & Metrics
-  ![Image](https://github.com/user-attachments/assets/a68bd012-9669-4f75-8cda-d340d0ff1c3b)

### Ad Trends & ROI
-  ![Image](https://github.com/user-attachments/assets/3c44c9e1-13d9-4e92-8dec-b1a7b258c1c4)

### Canpaign & Ad Performance
-  ![Image](https://github.com/user-attachments/assets/52639829-4e40-4ab2-b0d9-6956ca328cf4)



## <a name="link-to-dashboard"></a>Link to Dashboard
-  This is the link to access the Dashboard; https://app.powerbi.com/view?r=eyJrIjoiZmE2MjJjOTYtMjYwMi00MjdjLThiODMtYTEyMWFmZWNhZTU4IiwidCI6IjA1ODIyZmQwLTE5NmItNDBiMS1hOGE0LTAxMWI1YjVlZjA5NSJ9&pageName=ReportSectionb5f0c74e5605f2ba92cb&disablecdnExpiration=1745622071



## <a name="business-questions-and-answers"></a>Business Questions and Answers
#### Campaign Performance:
1. Which campaign generated the highest number of impressions, clicks, and conversions?
   -   The Fall Campaign generated the highest engagements all round with impressions (25M), Clicks (340K) and Conversions (60k)

2. What is the average cost-per-click (CPC) and click-through rate (CTR) for each campaign?
   -   Fall led in engagement with a 1.32% CTR, and also had the highest CPC at £0.93. Spring showed a good balance with 1.21% CTR and £0.86 CPC, while Summer had the lowest         CTR at 1.12% and a CPC of £0.88, making it the least efficient overall.

#### Channel Effectiveness:
3. Which channel has the highest ROI?
   -   Pinterest leads with a 2151% ROI, significantly outperforming Instagram (980%) and Facebook (476%). This suggests Pinterest as the most cost-effective and high-  performing channel for driving returns.

4. How do impressions, clicks, and conversions vary across different channels?
   -   Instagram drove strong engagement and results with 19.36M Impressions, 275K clicks, and 62K conversions, leading in conversions overall. Facebook had the highest Impressions (21.76M) and 280K clicks, but slightly fewer conversions at 53K. Pinterest, while having the lowest Impressions (17.64M), still achieved 172K clicks and 46K conversions, showing efficient performance relative to reach.

#### Device Performance:
5. How do ad performances compare across different devices (mobile, desktop, tablet)?
   -   For the Collection ad, Mobile generated 19 million impressions, surpassing	 Desktop's 13 million. Similarly, the Discount ad, which only ran on mobile, garnered 16 million impressions while on Desktop it garnered 10 million impressions.

6. Which device type generates the highest conversion rates?
   -   Yet, despite Mobile's wider reach, its conversion rate sits at 20%, while Desktop boasts a higher 24% conversion rate.

#### Ad-Level Analysis:
7. Which specific ads are performing best in terms of engagement and conversions?
   -   The Discount ad not only delivered the highest ROI at 1080%, but also converted users at a strong 28% rate. In comparison, the Collection ad, while still effective, achieved a lower ROI of 812% and a conversion rate of 18%.

8. What are the common characteristics of high-performing ads?
   -   High-performing ads share several key characteristics that drive strong ROI. First, they exhibit notably high conversion rates—for example, the Discount ad on desktop during the summer achieves a 45% conversion rate while the Collection ad on desktop reaches 30% in the same period. Along with these robust conversion rates, these ads maintain low cost per acquisition (CPA) and relatively modest cost per click (CPC), ensuring that each click converts efficiently without overspending. Additionally, high-performing ads yield impressive ROI figures—ranging from around 1200% to over 1400% in the summer—demonstrating that effective spending translates directly into substantial returns. Finally, while performance can vary by device, desktop placements often outperform mobile, indicating that the ad format or user experience on larger screens may contribute to more effective engagement. These combined factors highlight that strategically optimizing for higher conversion rates while keeping acquisition costs low is the key driver behind these exceptional ROI results.


#### ROI Calculation:
9. What is the ROI for each campaign, and how does it compare across different channels and devices?
   -   Desktop consistently outperformed mobile across all campaigns. For the Summer campaign, desktop delivered an ROI of 1359% compared to 1257% on mobile. A similar pattern followed in Spring (941% vs. 866%) and Fall (887% vs. 798%). When looking at ROI by channel, Pinterest consistently led across all campaigns. In the Summer campaign, Pinterest drove a massive 2118% ROI, followed by Instagram at 1379% and Facebook at 884%. The trend continued in Spring with Pinterest at 2303%, Instagram at 934%, and Facebook at 398%. In Fall, Pinterest again led with 2082%, while Instagram followed at 833%, and Facebook at 357%.

10. How does spend correlate with conversion value across different campaigns?
    -   As Spend increases, Total conversion value also tends to increase. This suggests that higher investment (Spend) is often accompanied by higher returns (Conversion value), although the relationship is not perfectly linear (there’s a lot of scatter). The analysis of Spend and Total conversion value across campaigns reveals a positive correlation, where higher investment generally leads to higher returns. However, the relationship is not perfectly linear, as some lower spend levels within observed clusters yielded stronger returns than higher spend levels, indicating inefficiencies in budget allocation.


#### Time Series Analysis:
11. Are there any noticeable trends or seasonal effects in ad performance over time?
    -    The ad performance data reveals seasonal trends both in terms of engagement and conversion. In March (Q1), the Collection ad garnered around 45,524 clicks from approximately 3.49 million impressions, resulting in 8,320 conversions, while the Discount ad showed a slightly different pattern with 32,040 clicks but a higher conversion count of 9,700 despite slightly fewer impressions. A noticeable shift occurs in Q3, where engagement begins to climb. In September, the Collection ad’s click volume jumps to 63,420, accompanied by almost 4.47 million impressions, though conversions slightly dip to 7,680. The Discount ad in September also registers a substantial increase, reaching 48,340 clicks and 9,916 conversions from about 3.98 million impressions. 
The upward trend continues into Q4, with October and November exhibiting some of the highest performance figures of the year. In October, the Collection ad reaches 67,876 clicks with 4.71 million impressions and 9,496 conversions, and the Discount ad likewise performs robustly with over 50,000 clicks and 11,128 conversions. In November, performance remains strong, with both ads maintaining high levels of engagement and conversion. These increases in clicks and impressions in Q3 and Q4 indicate that later in the year, possibly due to seasonal promotions or heightened consumer activity, the ads resonate more with the target audience, leading to improved overall performance.



## <a name="recommendations"></a>Recommendations
1. Other Campaigns should focus on implementing the strategy used for the Fall Campaigns, optimizing for engagements rather than just reach.
2. To maximize campaign effectiveness, we should consider optimizing the Mobile experience for better conversions while exploring whether discount ads could perform well on Desktop, where users are already converting at a higher rate.
3.  To maximize returns, refining the "Collection" ad or blending "Discount" strategies into it could unlock greater performance, also  increasing investment in the Discount ad since it is driving the highest profitability and efficiency.
4.  Allocate more budget to Pinterest, as it consistently generates the highest ROI, making it the most valuable platform for conversions.
5.  Re-evaluate Facebook’s ad strategy, as it has the lowest ROI share. Testing new creatives, refining audience targeting, or shifting budget to better-performing channels may improve its performance.
6.  For the Trends in Ad engagements per month, more of the ad budget should be reallocated into Q3 and Q4, when both clicks and conversions naturally climb. By increasing spend and broadening reach during these high‑engagement months, we will capture peak consumer interest and drive even greater returns.
7.  Reallocate more of our budget toward the "Ad–Desktop" combinations that consistently deliver the highest conversion rates and ROI during peak periods. By prioritizing spend where it works best, we will maximize return without simply pouring more money into underperforming channels.







## <a name="conclusion"></a>Conclusion
-  This analysis explores key dimensions of campaign performance, including channel effectiveness, device efficiency, ad-level impact, seasonal trends, and ROI distribution.  It highlights high-ROI opportunities, seasonal trends, and cost-efficient strategies; providing clear guidance to optimize spend, improve targeting, and maximize overall campaign profitability.

















