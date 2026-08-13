Electric Vehicle Population Analysis 🔋

An interactive Tableau dashboard exploring the growth, market leaders, and clean-fuel eligibility of electric vehicles registered with the Washington State Department of Licensing (DOL).

Show Image

📊 Overview

This project analyzes 150,000+ electric vehicle registrations to answer three core questions:

How fast is EV adoption growing, and when did growth accelerate?
Which makes and models dominate the current EV population?
How many vehicles qualify for Clean Alternative Fuel Vehicle (CAFV) incentives?

🗂 Data Source
Dataset: Electric Vehicle Population Data — Washington State Dept. of Licensing
Records: 150,422 unique vehicle registrations
Fields: Make, Model, Model Year, Electric Vehicle Type, CAFV Eligibility, Electric Range, State/County/City, Postal Code

🛠 Tools & Techniques
Tableau Desktop for data visualization and dashboard design
Calculated fields using COUNTD, AVG, and conditional IF logic
Dashboard actions and filters (State, Make, Model, CAFV Eligibility) for interactive, self-service exploration
Chart types: KPI cards, area chart, horizontal bar chart, donut chart, filled map

📈 Key Insights
Metric	Value
Total Registered Vehicles	150,422
Average Electric Range	67.83 miles
Battery Electric (BEV)	~116.7K (77.6%)
Plug-in Hybrid (PHEV)	~33.6K (22.4%)
Top Make	Tesla (~51% of all registrations)
CAFV Eligible	~41.8%
EV adoption accelerated sharply after 2017, roughly doubling by 2021.
Tesla alone accounts for about half of all registered EVs — more than the next nine makes combined.
Nearly half of records show "CAFV Unknown" status, highlighting a data-completeness gap for incentive eligibility.
Registrations are heavily concentrated in Washington State, with a small share of out-of-state owners.

📁 Repository Contents
├── Tableau_Project_For_Mock.twb   # Tableau workbook (data source connection)
├── dashboard_preview.png          # Dashboard screenshot
└── README.md

BY Prasad Chede
