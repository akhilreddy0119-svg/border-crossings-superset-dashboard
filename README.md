BORDER CROSSINGS SUPERSET DASHBOARD
Exploring U.S. Border Crossings (1996–2025): Seasonal Patterns, Transportation Modes & COVID-19 Impacts

This project analyzes 38K+ U.S. Border Crossing records from the Bureau of Transportation Statistics (BTS) using Apache Superset.
The goal was to explore the data and tell a story around:

US–Mexico vs US–Canada border trends

Seasonal & cyclical patterns in travel

Transportation mode differences

Impacts of major world events (COVID-19)

All insights are presented through 6 fully-interactive Superset visualizations.

📁 Repository Structure
├── charts/                 # Exported chart screenshots (PNG)
├── data/                   # Original dataset & documentation
├── superset_export/        # Superset export (.zip) for full dashboard import
└── README.md               # Project overview (this file)

📊 Dashboard Overview

Below is the story the dashboard tells, followed by insights from each chart.

1️⃣ Total Crossings by Border (1996–2025) — Pie Chart

Goal: Compare total volume between the US–Mexico and US–Canada borders.

Insight:

US–Mexico dominates total crossings—nearly 75–80% of all recorded traffic.

US–Canada accounts for the remaining volume, much smaller but more stable.

Story Point: The U.S.–Mexico border is the primary driver of cross-border movement, heavily influencing national mobility patterns.

2️⃣ Total Crossings Over Time (1996–2025) — Time-Series Line Chart

Goal: Analyze long-term movement trends across both borders.

Insights:

Strong yearly cycles visible at Mexico border—peaks in summer, dips in winter.

A major drop in 2020 clearly marks COVID-19 border lockdowns.

Post-COVID recovery is steep at Mexico border but slow at Canada border.

Story Point: Border mobility strongly reflects economic and global events, with 2020 showing an unprecedented collapse.

3️⃣ Transportation Mode Comparison (All Years) — Bar Chart

Goal: Compare cumulative totals across transportation modes.

Includes:

Personal Vehicles

Pedestrians

Trucks

Buses

Trains

(Excluded: Personal Vehicle Passengers, Bus Passengers, Rail Containers, Train Passengers, Truck Containers — as per assignment)

Insights:

Personal Vehicles dominate at both borders.

Pedestrian crossings significantly higher at Mexico border.

Truck traffic grows steadily at both borders but is more stable.

Story Point: Travel behavior and economic movement differ sharply between borders, with Mexico showing higher foot traffic and Canada showing balanced vehicle/truck usage.

4️⃣ Monthly Seasonality Pattern (1996–2025) — Line Chart

Goal: Identify cyclical monthly behavior.

Insights:

Mexico border shows repeating waves every year → clear seasonality.

Canada border shows weaker seasonality, with smoother fluctuations.

August consistently appears as peak month for Mexico border.

Story Point: Travel demand follows predictable seasonal cycles—critical for transportation planning and staffing.

5️⃣ Impact of COVID-19 on Border Crossings (2018–2022)

Goal: Zoom into the COVID event window.

Insights:

In March–April 2020, total crossings collapsed by almost 70–80%.

Slow recovery through 2021.

By 2022, crossings approach pre-pandemic levels but do not fully stabilize.

Story Point: COVID-19 caused the largest mobility disruption in the dataset’s 30-year history, visible instantly in the time-series curve.

6️⃣ Trends of Transportation Modes Over Time (1996–2025)

Goal: Show all mode trends in one composite view.

Insights:

Personal Vehicles consistently dominate but show long-term decline after 2008.

Pedestrian traffic stable until COVID dip, then gradually rising.

Trucks remain steady with slight upward trend.

Buses and Trains stay extremely low.

Story Point: Each transportation mode reacts differently to economic & global events—vehicles drop sharply, trucks remain stable, pedestrians collapse during COVID.

🧠 Key Takeaways from the Entire Dashboard
1. Mexico Border Drives U.S. Cross-Border Activity

Higher traffic, stronger cycles, and faster COVID recovery.

2. Strong Seasonal Behavior Exists

August and summer months peak nearly every year, especially at Mexico border.

3. Transportation Modes Behave Differently

Personal Vehicles dominate, trucks remain stable, and pedestrians fluctuate heavily.

4. COVID-19 Was a Massive Disruption

The sharp dip in 2020 is visible in every chart—demonstrating real-world event impact.

5. Superset Enables Powerful Storytelling

With line charts, bar charts, and custom filters, the dataset becomes highly explainable.
