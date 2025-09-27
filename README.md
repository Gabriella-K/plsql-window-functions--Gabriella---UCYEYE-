#**Project Overview**

This project analyzes telecom customer usage in Rwanda using PL/SQL with window functions.
We designed a database schema with customers, services, and usage_records tables, 
then applied ranking, aggregate, navigation, and distribution queries to uncover customer frequency and spending patterns.

##**Database Schema**

customers → Stores customer details (ID, name, region, join date).

services → Catalog of telecom services (data, voice, SMS, mobile money).

usage_records → Logs of customer transactions with services, amounts, and dates.

##**Window Functions Implemented**

Ranking → Identify top customers by spending.

Aggregate → Running totals, moving averages, min/max trends.

Navigation → Month-over-month growth comparisons.

Distribution → Customer segmentation (quartiles & cumulative distribution).

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
