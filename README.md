# HR Analysis

### Table of Contents

- [Project Overview](#Project-Overview)
- [Data Source](#Data-Source)
- [Tools](#Tools)
- [Data Cleaning/Preparation](#Data-Cleaning/Preparation)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Analysis](#Data-Analysis)
- [Results/Findings](#Results/Findings)
- [Recommendations](#Recommendations)
- [Reference](#Reference)


### Project Overview

Analyze employee attendance/leave patterns to optimize workforce planning, improve productivity and enhance employee satisfaction.

### Data Source
HR Analysis: RosesnTech Attendance Sheet.Xslx file, containing detailed information about the data https://codebasics.io/resources/resume-project-data-analytics 

### Tools
- Excel (Data Cleaning)
- Powerbi (Data Transformation)
- Powerbi (DAX)
- Powerbi (Creating report)

### Data Cleaning/Preparation

- Data loading and Inspection
- Data cleaning and formatting

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key business questions:

1. Identify Attendance Patterns.
2. Evaluate Departmental/Team Performance.
3. Determine Leave Utilization.
4. Provide actionable insights for HR/management.

### Data Analysis

Measures 
- Attendance percentage: Attendace % = DIVIDE([Present Days],[Office Working days],0)
- Work from home perecntage: WFH % = DIVIDE([WFH Count],'Measures (2)'[Present Days],0)
- Sick leave percentage: SL % = DIVIDE('Measures (2)'[SL Count], [Office Working days])
- Data modelling in Powerbi

### Results/Findings

The analysis results are summarized as follows:

1. Excellent Attendance Rate: 94% attendance rate indicates a highly committed workforce.
2. Low Sick Leave Frequency: 0.4% sick leave usage suggests effective health management.
3. Moderate WFH Usage: 9.1% WFH usage indicates flexibility and potential productivity benefits.
4. Absenteeism: 6% of employees had unauthorized absences.


### Recommendations

1. Continue encouraging attendance, recognizing and rewarding employees.
2. Expand health programs to maintain low sick leave rates.
3. Monitor WFH effectiveness, gather feedback, and adjust policies.
4. Regular feedback sessions to identify areas for improvement.
5. Ensure adherence to labor laws, regulations, and company policies.

### Reference

Codedbasics: (#https://codebasics.io/resources/resume-project-data-analytics)














