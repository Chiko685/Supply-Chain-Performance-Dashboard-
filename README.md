## Supply Chain & Logistics Performance Analysis: End-to-End Analytics
This project features a comprehensive analysis of logistics operations across Southeast Asia. By integrating data processing with interactive visualization via Tableau Public, the study evaluates fleet efficiency, delivery reliability, and cost-effectiveness to drive supply chain optimization.

## 📊 Business Objectives

- The analysis provides data-driven insights into the following core logistics components:
- Delivery Reliability: Quantifying bottlenecks by comparing expected vs. actual delivery times.
- Quality Control: Tracking shipment integrity through damage rates and insurance claims.
- Cost Optimization: Evaluating shipping expenditures across diverse fleets and cross-border destinations.
- Fleet Benchmarking: Performance auditing of key providers: StreamFlow, NexusGlobal, EchoLogistics, and BridgeChain.

## 🛠️ Tech Stack

- Analysis & ETL: Python (Pandas) / SQL / Excel
- Visualization: Tableau Public (Interactive Dashboards)
- Regional Scope: Indonesia, Thailand, Philippines, Singapore, Brunei, and Vietnam.

## 📈 Key Analysis Features
1. Delivery Time Variance & Reliability

The analysis measures the delta between Expected and Actual delivery times. This KPI identifies specific logistical lanes or providers that consistently exceed delivery windows.

2. Risk & Quality Assessment

By correlating Damaged goods with Claim data, the project pinpointed high-risk routes. This allows for targeted improvements in handling protocols and packaging standards.

3. Shipping Cost Efficiency

Analysis of Shipping Cost relative to Order Count identifies economies of scale. We utilize this to determine which fleets provide the highest ROI for specific geographic clusters.

## 📊 Interactive Visualization (Tableau Public)

- The results of this analysis are hosted on Tableau Public, providing a dynamic "Logistics Command Center" experience.
- Geospatial Mapping: Visualizing regional performance across Southeast Asia.
- Fleet Leaderboards: Real-time ranking of logistics providers based on speed and safety.
- Trend Analysis: Monitoring shipping volumes and cost fluctuations over time.
  
<img width="837" height="546" alt="Screenshot 2026-02-02 at 14 54 54" src="https://github.com/user-attachments/assets/5fe34954-c09d-448e-9abd-ea80d6c91e52" />


## 💻 Sample Logic: Identifying High-Delay Fleets

The following Python snippet demonstrates the preliminary data processing used before exporting to Tableau:

<img width="711" height="546" alt="Screenshot 2026-02-02 at 14 56 00" src="https://github.com/user-attachments/assets/8eda9f1c-4ecb-44c4-9814-ebd5ac8a2b09" /> 

## 🚀 How to Use

- Data Prep: Review the Dataset Liveclass Week 5 for raw logistical entries.
- Analysis: Run the Python/SQL scripts to generate the aggregated performance metrics.
- Visualization: Access the Tableau Public dashboard to interact with the findings and explore regional data filters.
