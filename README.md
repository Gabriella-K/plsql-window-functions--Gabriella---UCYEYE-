**Resources**

https://techcabal.com/2025/06/12/rwanda-internet-penetration-rate/,

https://www.ecofinagency.com/news/3107-47923-mtn-rwanda-faces-service-issues-amid-network-investment-push,

https://www.apc.org/sites/default/files/CICEWARwanda_20090908_0.pdf,

https://www.youtube.com/watch?v=rIcB4zMYMas&t=12s,

https://www.youtube.com/watch?v=Ww71knvhQ-s

#**Project Overview**

This project analyzes telecom customer usage in Rwanda using PL/SQL with window functions.
We designed a database schema with customers, services, and usage_records tables, 
then applied ranking, aggregate, navigation, and distribution queries to uncover customer frequency and spending patterns.

##**Database Schema**

customers → Stores customer details (ID, name, region, join date).

services → Catalog of telecom services (data, voice, SMS, mobile money).

usage_records → Logs of customer transactions with services, amounts, and dates.

![img alt](https://github.com/Gabriella-K/plsql-window-functions--Gabriella---UCYEYE-/blob/612c8e00ee352cbe0a2594349dec57696f9778cc/ERdiagram.png)

##**Window Functions Implemented**

Ranking → Identify top customers by spending.
![img alt](https://github.com/Gabriella-K/plsql-window-functions--Gabriella---UCYEYE-/blob/9306e905a1e05a8faca4c17213a0629b9ed835c6/Screenshots/Ranking.png)

Aggregate → Running totals, moving averages, min/max trends.
![img alt](https://github.com/Gabriella-K/plsql-window-functions--Gabriella---UCYEYE-/blob/630cf24c887bad5a82c8928abd89b9bddc4c6634/Screenshots/Aggregate.png)

Navigation → Month-over-month growth comparisons.
![img alt](https://github.com/Gabriella-K/plsql-window-functions--Gabriella---UCYEYE-/blob/85e1013ae8935a9d7d0fee46b054c4a9d38720c7/Screenshots/Navigation.png)

Distribution → Customer segmentation (quartiles & cumulative distribution).
![img alt](https://github.com/Gabriella-K/plsql-window-functions--Gabriella---UCYEYE-/blob/b0c4a2d01110c1a8d220d167b3edf28d19d9e93f/Screenshots/Distribution.png)

##**Results Analysis**

**Descriptive**:
The data shows the top customers by revenue, regional usage patterns, and month-to-month changes in telecom service consumption. 
Some customers have significantly higher usage, while others fall in lower quartiles.

**Diagnostic**:
High-value customers are concentrated in certain regions, possibly due to better coverage or targeted plans. 
Growth fluctuations are linked to seasonal demand and customer switching between plans.

**Prescriptive**:
Focus retention efforts on top-quartile customers, improve service in underperforming regions, and design flexible plans to smooth out seasonal declines. 
Regular monitoring with window functions will help optimize marketing and customer support strategies.

**Integrity statement**
All sources were properly cited. Implementations and analysis represent original work. No AI generated content was copied without attribution or adaptation.

created bv Gabriella UCYEYE  27673
Date:29/09/2025
