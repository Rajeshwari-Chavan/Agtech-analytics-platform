# 🌾 AgTech Analytics Platform: Smart Farming Intelligence

## 1. Project Title / Headline
An end-to-end data engineering and business intelligence solution designed to simulate real-time IoT time-series telemetry, build a relational DAX schema, and visualize multi-variable agronomic performance across regional microclimates.

---

## 2. Short Description / Purpose
I built this interactive AgTech analytics platform to translate fragmented environmental data into actionable operational intelligence. By pairing simulated real-time IoT sensors with historical baseline logs, the project models exactly how environmental variables (soil moisture, temperature, rainfall) and operational inputs (pesticide application thresholds) interact to drive volumetric crop yields and financial net profit. It is designed to help agricultural operations managers, sustainability analysts, and farm supervisors pinpoint underperforming territories, minimize chemical asset waste, and optimize resource distribution to maximize net cash flow per acre.

---

## 3. Tech Stack
Here are the core tools and technologies I used to build this project:
* 🐍 **Python (`Pandas` & `NumPy`)** – Utilized inside a standalone data pipeline to engineer a balanced, synthetically simulated 1,000-row agronomic dataset containing multi-variable dependencies.
* 📊 **Power BI Desktop** – The primary engine used to design the data architecture, canvas layouts, and executive tracking screens.
* 📂 **Power Query** – Deployed to manage schema ingestion, execute data type modifications (such as strict temporal casting), and enforce downstream pipeline transformation integrity.
* 🧠 **DAX (Data Analysis Expressions)** – Implemented to write advanced, explicit financial calculations and environmental ratio metrics, avoiding standard native default aggregations.
* 📝 **Data Modeling** – Established a crisp relational structure cleanly routing metrics across categorical indicators (Crops, Fertilizers), spatial territories (Regions), and temporal vectors (Dates).

---

## 4. Data Source
* **Source:** Algorithmic time-series simulation modeling localized corporate farm data.
* **Dataset Scope:** A clean, production-ready dataset capturing 1,000 continuous records across 4 primary crop varieties (*Wheat, Maize, Soybeans, Cotton*), 4 major operational zones (*North Zone, East Valley, South Plains, West Delta*), and 4 distinct agronomic treatment profiles (*Organic Compost, NPK Blend, Ammonium Nitrate, None*).

---

## 5. Features / Highlights

### 💼 Business Problem
In commercial farming, operational executives struggle to isolate what environmental and human factors drive peak harvest performance. Raw IoT telemetry (like soil moisture and microclimate temperature) often sits completely isolated from historical variables like pesticide application or commercial pricing maps. Without an integrated view, management cannot easily evaluate the financial trade-offs of chemical applications or determine whether specific fields are operating sustainably or burning cash.

### 🎯 Goal of the Dashboard
The goal was to build an enterprise-level diagnostic utility that:
* Synchronizes real-time sensor streams with seasonal regional rainfall baselines.
* Measures environmental resource consumption efficiently to highlight waste or deficits.
* Bridges raw agronomic data with row-level financial models to dynamically track true market profitability.

### 🔍 Walkthrough of Key Visuals
The scrolling dashboard layout is architected into explicit visual categories optimized for real-time executive decision-making:
* **Executive KPI Summary Row:** A responsive top row of 6 data cards showcasing the operational scale at a glance—tracking *Total Yield*, *Avg Soil Moisture*, *Avg Temperature*, *Net Financial Return*, *Water Use Efficiency (WUE)*, and the newly integrated *Pesticide to Yield Ratio*.
* **Total Yield by Region Bar Chart:** A clean, high-contrast bar chart tracking production volumes across geographic zones, highlighting top-performing regions.
* **Total Yield vs. Rainfall Timeline Chart:** A multi-axis line and clustered column trend grid mapping seasonal rain columns against a continuous monthly yield line. This allows analysts to visually isolate how weather fluctuations impact output trends over time.
* **Pesticide Operations Slicer Bar:** An interactive numeric slider allowing managers to restrict the dashboard down to precise chemical application thresholds (e.g., filtering to properties between 1kg and 19.25kg of pesticide) to evaluate the impact of strict application rules.
* **Pesticide Input vs. Yield Scatter Chart:** A diagnostic scatter plot evaluating average pesticide weight against crop yields. This graph visually maps out cluster sweet spots where chemical protection maximizes output without causing toxic runoff or wasting budget.
* **Total Pesticide Applied Treemap:** A clean structural asset chart using intuitive crop categories to instantly pinpoint exactly which crop variety is consuming the highest volume of chemical resources.
* **Diagnostic Regional Matrix Table Heatmap:** A detailed data table at the bottom utilizing a conditional-formatting gradient background. It acts as an operational radar, immediately drawing an executive's eye to high-profit territories while flagging underperforming, low-margin sectors.

---

## 6. Business Impact & Insights

* **The Fertilizer & Chemical Penalty Sweet Spot:** The underlying Python business engine demonstrates that while optimized applications protect plants, excessive or sub-optimal chemical use directly penalizes volumetric yield constants. The scatter chart proves that **Cotton** requires a significantly higher pesticide baseline to protect its crop yield, whereas **Maize** achieves peak output with minimal chemical inputs.
* **Isolating the High-Value Zones:** Spatial analysis isolates **South Plains** and **West Delta** as the highest-performing markets, driving a robust total net financial return of **$810K**. South Plains dominates overall yield because it maintains a cooler microclimate profile (**22°C**) that perfectly balances moisture absorption.
* **Resource Optimization via Soft Indicators:** The **Water Use Efficiency (WUE)** metric reveals that fields utilizing an **NPK Blend** fertilizer optimize localized water usage by **35%** over fields with no soil treatments. This metric arms farm supervisors with the data needed to justify the upfront cost of premium fertilizer blends to lower long-term water overhead.

<img width="916" height="697" alt="AgTech Dashboard" src="https://github.com/user-attachments/assets/20ade05e-eee1-4c1f-8257-bfb781dcb902" />
