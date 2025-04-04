# Canadian Healthcare Wait Times Analysis (2018-2023)

This project aims to analyze healthcare wait times across Canadian provinces and territories, focusing on surgical procedures, diagnostic scans, and other critical medical services. The motivation stems from a personal experience where a 30-day wait to see a family doctor highlighted systemic delays in Canada’s healthcare system. Compared to more accessible healthcare in countries like India, this disparity raised concerns about efficiency and patient outcomes, especially for urgent or major treatments.

## Dataset
The dataset for this analysis primarily comes from the Canadian Institute for Health Information (CIHI), specifically their Wait Time Metadata repository ([link](https://www.cihi.ca/en/wait-time-metadata)). Here’s why this is a credible and comprehensive source for analyzing Canadian healthcare wait times:

Data Source: Canadian Institute for Health Information (CIHI)
CIHI is Canada’s official national health data organization, funded by federal and provincial governments. It collects standardized wait time data from all provinces/territories, ensuring:

- Reliability: Data is reported by hospitals/clinics under strict guidelines.
- Comparability: Metrics (e.g., 50th/90th percentile waits) are calculated uniformly.
- Coverage: Includes major procedures

Healthcare Wait Times Visualization
![image](https://github.com/user-attachments/assets/e9bb9777-c0ed-4b68-98c6-07be13d60e90)

![image](https://github.com/user-attachments/assets/d75c9966-4e51-47ce-8ee9-4b61636b2f7a)

![image](https://github.com/user-attachments/assets/5b795ff6-5828-4f04-a2af-557809d6a90e)



📌 Project Overview

This project examines healthcare wait times for critical procedures (surgeries, cancer treatments, and diagnostics) across Canadian provinces. It identifies:
* Worst-performing regions (longest delays)
* Best practices from efficient provinces
* Trends over time (pre/post-pandemic)

Key Question: 
Which provinces struggle most with wait times, and what can we learn from top performers?
🛠️ Technical Details
Tools & Technologies
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook / Google Colab
- Data Sources: Government reports (CIHI, provincial health databases)

Methodology

Data Cleaning:
* Standardized inconsistent wait time definitions (e.g., "referral-to-treatment" vs. "diagnosis-to-surgery")
* Handled missing values using median imputation

Analysis:
* Benchmarking against CIHI targets
* Year-over-year (YoY) change analysis

Visualization:
* Interactive trend charts
* Provincial performance heatmaps

🔍 Key Findings

Worst Delays in 2023:
* PEI: 623-day waits for cataract surgery (+65% vs. 2018)
* Nova Scotia: 176 days for bladder cancer surgery (+93% YoY)

Top Performers:
* Ontario: 18-day radiation therapy waits (below 28-day national benchmark)
* Saskatchewan: 35-day avg. for bladder cancer surgeries (best in Canada)

Trends:
* Elective surgeries (e.g., knee replacements) saw the largest backlogs post-pandemic.
