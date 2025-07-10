# AQI-Project
📊 Renewable Energy Subsidy Impact Analysis Based on Air Quality Index (AQI)
This project analyzes the potential impact of a proposed U.S. federal policy that aims to offer subsidies for renewable energy in states where the average Air Quality Index (AQI) is 10 or above. The analysis specifically focuses on the operations of Ripple Renewable Energy (RRE), which currently operates in the following states:

California
Florida
Michigan
Ohio
Pennsylvania
Texas
The goal is to identify which of these states are most likely to qualify for subsidies under the proposed policy, based on their average AQI levels.

🎯 Objective
Analyze AQI data for the six operational states of Ripple Renewable Energy.
Apply statistical analysis and hypothesis testing to assess the likelihood of each state qualifying for the subsidy.
Provide clear, data-driven recommendations for RRE’s strategic decision-making.


🛠️ Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebooks
Data Visualization Libraries

📊 Key Findings
Hypothesis 1:
The p-value (0.049) is below the 0.05 threshold, leading to rejection of the null hypothesis.
➡️ A metropolitan strategy may be effective for renewable energy targeting based on AQI levels.

Hypothesis 2:
With a p-value of 0.030 and a negative t-statistic (-2.036), we reject the null hypothesis.
➡️ New York has a significantly lower average AQI compared to other regions at the 5% significance level.

Hypothesis 3:
Despite a negative t-statistic (-1.74), the p-value (0.940) exceeds 0.05. We fail to reject the null hypothesis.
➡️ There is no significant evidence that Michigan’s average AQI exceeds 10.
Michigan may not qualify for the proposed renewable energy subsidy under the new policy.
