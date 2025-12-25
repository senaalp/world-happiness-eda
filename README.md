# world-happiness-eda
Performed end-to-end EDA on the World Happiness Report 2021 dataset using pandas/numpy, including distribution analysis and data quality checks.  
Key Findings (Metrics)

Primary metric: Pearson correlation coefficient (r) between each feature and Life Ladder (happiness score).

Top positive associations with Life Ladder:

Logged GDP per capita: r = 0.79

Healthy life expectancy: r = 0.74

Social support: r = 0.71

Freedom to make life choices: r = 0.53

Top negative associations with Life Ladder:

Perceptions of corruption: r = -0.43

Negative affect: r = -0.30

Interpretation: Higher GDP, health, social support, and freedom are strongly/moderately associated with higher happiness scores, while higher perceived corruption and negative affect are associated with lower happiness. (Correlation describes association, not causation.)
