# NHANES Cardiovascular Health Analysis

This repository contains code and analysis for investigating cardiovascular health among participants from the NHANES (National Health and Nutrition Examination Survey) March 2020 Pre-Pandemic Data. The focus is on identifying individuals suffering from heart issues, analyzing the distribution by age groups, gender, and other demographic factors.
Project Overview

### Data Files

    P_DEMO.xpt: Contains demographic data, including age, gender, ethnicity, education, marital status, and more.
    P_CDQ.xpt: Contains data related to cardiovascular health, including pain, discomfort, and other cardiovascular-related indicators.

Key Variables Used:

    Demographics:
        SEQN: Respondent sequence number
        RIDAGEYR: Age in years
        RIAGENDR: Gender
        DMDEDUC2: Education level
        RIDRETH1: Race/Hispanic origin
    Cardiovascular Health:
        CDQ001 to CDQ010: Various indicators for pain, discomfort, shortness of breath, etc., related to heart issues.
## Summary of the result
```
Summary of Results:
{'Total People with Heart Conditions': 3202, 'Gender Distribution': RIAGENDR
2.0    3261
1.0    3172
Name: count, dtype: int64, 'Heart Condition by Gender': RIAGENDR
2.0    1733
1.0    1469
Name: count, dtype: int64, 'Heart Condition by Age Group': Age_Group
10-20      0
21-30      0
31-40      0
41-50    617
51-60    767
61-70    890
70+      928
dtype: int64, 'Heart Condition Percentage by Age Group': Age_Group
10-20          NaN
21-30          NaN
31-40          NaN
41-50    42.669433
51-60    49.009585
61-70    50.973654
70+      55.369928
dtype: float64}
```
