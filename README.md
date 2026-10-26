UK New Car and Van Registrations: Power BI Dashboard

A three-page Power BI dashboard on how the UK new car and van market has changed since 2014, built from official DfT/DVLA vehicle licensing statistics.

Scenario: This is a portfolio project. The business case (a fleet company deciding what vehicles to buy) is fictional. The data is real and public.

Business question

Which vehicles and fuel types is the UK market moving towards, and which makes are winning?

Key findings

1. The market has not recovered to its pre-2019 size. Quarterly registrations peaked at about 0.83M in 2017, fell to 0.17M in 2020, and have since sat at roughly 0.5M to 0.6M. The latest quarter was 539K, up 13.98% on the same quarter last year.

2. Electric has grown from almost nothing to about one in five new vehicles. Battery electric share rose from 0.34% in 2014 to 20.98% in 2025 (22.51% so far in 2026).

3. Diesel has collapsed. Diesel fell from 55.94% of registrations in 2014 to 13.80% in 2026. In 2025 alone, diesel fell 15.6% and petrol fell 18.5%.

4. Hybrids are growing fast too. In 2025, plug-in hybrids grew 39.1% and battery electric grew 24.6%. Hybrid and plug-in hybrid together were about 38% of 2025 registrations.

5. Cars grew while vans fell. 2025 total: 2,401,231 (+1.6%). Cars: 2,071,394 (+3.6%). Vans: 329,837 (-9.2%).

6. Volkswagen leads by a wide margin. Top makes in 2025: Volkswagen (187K), BMW (126K), Ford (120K), Audi (115K), Kia (113K). The best-selling model was the Ford Puma (55,376, +14.6%).

Dashboard pages
Page	Question it answers
1. UK new car and van registrations, 2014 to date	How big is the market and how has it changed?
2. Electric and hybrid are replacing diesel	Which fuel types are rising and falling?
3. Who is winning	Which makes and models lead in 2025?

Page 1 Page 2 Page 3

What I built
Cleaned and reshaped the data in Power Query (unpivot, filters, a custom Fuel Group column).
Built a Date table and linked it to the data.
Wrote DAX measures: Total Registrations, Fuel Share %, Electric Share %, Year-on-Year %, and Latest Quarter figures.
Designed a dark theme and three report pages with slicers and conditional formatting.
Wrote a Business Requirements Document (see below).
Tools

Power BI (Power Query, DAX), Excel, a custom JSON theme.

Recommendations (for the fictional fleet client)
Plan for a smaller diesel share. It is falling fast every year, so do not build a long-term buying plan around it.
Include hybrids and plug-in hybrids, not just full electric. They are growing faster than the market.
Prefer popular makes and models for resale and availability. The top makes hold a large share.
Limitations
This data covers new registrations only. It does not cover used cars, and it does not separate private, company or leasing buyers.
2026 is a partial year, so 2026 shares are year to date.
Growth rates for new models (for example BYD Seal, +1024.7%) come from a very small 2024 base and should be read with care.
The data does not explain why changes happened. Possible causes such as regulation or fuel prices are not tested here.
Files
File	What it is
UK_Fleet_Dashboard.pbix	The Power BI dashboard
BRD_UK_Vehicle_Registrations.docx	Business Requirements Document
UK_Fleet_Dashboard_Dark_v2.json	The custom theme
Dashboard_1/2/3.png	Screenshots of each page
Data source

Department for Transport and DVLA, Vehicle licensing statistics (new registrations by make, model and fuel type). Contains public sector information licensed under the Open Government Licence v3.0.

Next steps
Repeat the analysis in SQL, Excel and Python and check the numbers match.
Add a regional view.
Author

Amosh Roopsingh | LinkedIn
