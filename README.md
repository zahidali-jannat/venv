Invalid Traffic (IVT) Analysis
Overview
This project analyzes ad traffic data to detect patterns related to Invalid Traffic (IVT). The analysis focuses on comparing mean values of key metrics when IVT is greater than zero versus when it is zero, across different dates and time intervals.

Key Observations
When IVT > 0, the mean values of several important columns are noticeably higher compared to periods when IVT = 0.

The analysis was performed by selecting specific dates and calculating the mean metric values for each hour, allowing comparison across multiple dates.

Clear trends were observed: uplift in mean values when IVT is above zero, and a decrease when IVT is at or below zero.

Methodology
Data was grouped and analyzed by date and hour.

Mean values for all relevant columns were calculated for each time interval.

No external AI tools were used; all analysis was performed independently using Python and pandas.

Visualizations were created to clearly highlight the relationship between IVT and other metrics.

Future Work
Given more time (4–5 days), a machine learning model can be implemented to automatically detect and predict IVT anomalies.

Files
ivt_analysis.ipynb — Jupyter notebook containing code and step-by-step analysis.

README.md — Project documentation.

data/ — Sample datasets (if not confidential).

Requirements
Python 3.x

pandas

matplotlib (or seaborn)
