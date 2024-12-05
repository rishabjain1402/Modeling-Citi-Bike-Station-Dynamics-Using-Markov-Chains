# NYC Citibike Station Modeling

### README Description:
# NYC Citibike Station Modeling

This repository contains the final project for ORIE 5530: Modeling Under Uncertainty at Cornell Tech. The project involves analyzing NYC CitiBike data from July 2024 to study bike availability patterns and estimate the steady-state distribution of bikes at selected stations using discrete Markov chains.

## Project Overview
CitiBike is an integral part of NYC's transportation network. This project focuses on:
- **Analyzing ride data** to understand usage patterns.
- **Modeling bike availability** at three key stations:  
  - W 21 St & 6 Ave (Chelsea)  
  - West St & Chambers St (Financial District)  
  - 1 Ave & E 68 St (Upper East Side).  
- **Using Markov Chains** to estimate bike availability states and predict long-term behavior.

## Key Features
- Data preprocessing to clean anomalies and focus on relevant time blocks (weekday mornings and evenings).
- Transition probability matrix estimation for bike inflow and outflow at each station.
- Computation of stationary distributions to reveal long-term bike availability patterns.
- Insights into operational efficiency and recommendations for demand management.

## Methodology
1. **Data Collection & Preprocessing**:  
   - Cleaned rides with negative or excessively long durations.
   - Focused on trips starting or ending at selected stations.  
   - Divided weekdays into morning (6:00 AM–12:00 PM) and evening (4:00 PM–10:00 PM) blocks.

2. **Markov Chain Formulation**:  
   - Modeled bike availability as discrete states (0 to station capacity).
   - Estimated transition matrices based on observed data.  

3. **Stationary Distributions**:  
   - Computed long-term probabilities for bike availability.  

## Results
- Morning and evening bike availability patterns were consistent across stations, reflecting commuter behavior.
- Recommendations for operational strategies include redistributing bikes during evenings to meet morning demand.

## Files in This Repository
- **`ORIE5530_Final_Report.pdf`**: The project report detailing the methodology, results, and conclusions.
- **`ORIE5530_Final_Project.ipynb`**: Python notebook containing all code for data preprocessing, modeling, and analysis.

## Technologies Used
- Python
- Pandas
- Numpy
- Matplotlib

## Authors
- Dennis Chen  
- Rishab Jain  
- Jet Semrick  

## License
This project is for academic purposes and is not licensed for commercial use.  

---

Feel free to adjust any details based on specific project deliverables or additional findings!
