# BUSA8031_Covid19_Group_Project
COVID-19 Data Analysis Project
Objective:
The primary objective of this project is to derive actionable insights from the publicly available COVID-19 data that can inform health-related decision-making in Australia and support evidence-based interventions and policies.

Table of Contents for COVID-19 Data Analysis
1. Introduction

1.1 Background Information

1.2 Objective and Scope of Analysis

2. Data Importation and Preliminary Exploration

2.1 Importing Libraries and Datasets

2.2 Preliminary Data Exploration

3. Data Cleaning and Preprocessing

3.1 Handling Missing Values

3.2 Data Type Conversion

3.3 Feature Engineering

4. Exploratory Data Analysis (EDA)

4.1 Descriptive Statistics

4.2 Visual Exploration of Key Variables

4.3 Temporal Analysis of COVID-19 Trends

5. Clustering Analysis

6. Wave Analysis

6.1 Identifying and Analyzing Waves

6.2 Comparative Analysis of Different Waves

7. Pandemic Impact Analysis

7.1 Hospitalization Analysis

7.2 Excess Mortality Analysis

8. Vaccination Uptake and Impact Assessment

8.1 Vaccination Coverage Across Demographics

8.2 Correlating Vaccination and Case Trends

9. Policy Impact Analysis

9.1 Analyzing the Impact of Policies on Case Trends

9.2 Association Between Policies and Other Key Indicators

10. Data Pattern and Anomaly Detection

10.1 Investigating Reporting Patterns

10.2 Identifying and Analyzing Data Anomalies

11. Modeling and Prediction (if applicable)

11.1 Model Selection and Justification

11.2 Model Training and Validation

11.3 Interpretation of Model Outcomes

12. Conclusions and Insights

12.1 Key Findings

12.2 Policy Implications and Recommendations

13. Limitations and Future Work

13.1 Analysis Limitations

13.2 Suggestions for Future Analysis

14. Appendix

14.1 Additional Charts and Tables

14.2 Supplementary Analyses

15. References

### Metadata
The specific policy and response categories are coded as follows:

School closures:

0 - No measures

1 - recommend closing

2 - Require closing (only some levels or categories,
e.g. just high school, or just public schools)

3 - Require closing all levels

No data - blank

Workplace closures:

0 - No measures

1 - recommend closing (or work from home)

2 - require closing (or work from home) for some
sectors or categories of workers

3 - require closing (or work from home) all but essential workplaces (e.g. grocery stores, doctors)

No data - blank

Cancel public events:

0 - No measures

1 - Recommend cancelling

2 - Require cancelling

No data - blank

Restrictions on gatherings:

0 - No restrictions

1 - Restrictions on very large gatherings (the limit is above 1,000 people)

2 - Restrictions on gatherings between 100-1,000 people

3 - Restrictions on gatherings between 10-100 people

4 - Restrictions on gatherings of less than 10 people

No data - blank

Close public transport:

0 - No measures

1 - Recommend closing (or significantly reduce volume/route/means of transport available)

2 - Require closing (or prohibit most citizens from using it)

Public information campaigns:

0 -No COVID-19 public information campaign

1 - public officials urging caution about COVID-19

2 - coordinated public information campaign (e.g. across traditional and social media)

No data - blank

Stay at home:

0 - No measures

1 - recommend not leaving house

2 - require not leaving house with exceptions for daily exercise, grocery shopping, and ‘essential’ trips

3 - Require not leaving house with minimal exceptions (e.g. allowed to leave only once every few days, or only one person can leave at a time, etc.)

No data - blank

Restrictions on internal movement:

0 - No measures

1 - Recommend movement restriction

2 - Restrict movement

International travel controls:

0 - No measures

1 - Screening

2 - Quarantine arrivals from high-risk regions

3 - Ban on high-risk regions

4 - Total border closure

No data - blank

Testing policy

0 – No testing policy

1 – Only those who both (a) have symptoms AND (b) meet specific criteria (eg key workers, admitted to hospital, came into contact with a known case, returned from overseas)

2 – testing of anyone showing COVID-19 symptoms

3 – open public testing (e.g. “drive through” testing available to asymptomatic people)

No data

Contract tracing

0 - No contact tracing

1 - Limited contact tracing - not done for all cases

2 - Comprehensive contact tracing - done for all cases

No data

Face coverings

0 - No policy

1 - Recommended

2 - Required in some specified shared/public spaces outside the home with other people present, or some situations when social distancing not possible

3 - Required in all shared/public spaces outside the home with other people present or all situations when social distancing not possible

4 - Required outside the home at all times, regardless of location or presence of other people

Vaccination policy

0 - No availability

1 - Availability for ONE of the following: key workers/ clinically vulnerable groups / elderly groups

2 - Availability for TWO of the following: key workers/ clinically vulnerable groups / elderly groups

3 - Availability for ALL the following: key workers/ clinically vulnerable groups / elderly groups

4 - Availability for all three, plus partial additional availability (select broad groups/ages)

5 - Universal availability
