# CollegeAttendanceInsights
College Attendance Insights Dashboard (Power BI)

Interactive Power BI dashboard analyzing attendance patterns for 500+ students across multiple subjects.
The report identifies at-risk students, low-performing subjects, and attendance trends over time using a clean star-schema model and DAX-driven KPIs.

# Features

Attendance Heatmap: Student × Subject matrix with dynamic color-coding

Subject Performance View: Average attendance % per subject, sorted to highlight low turnout

At-Risk Detection: Flags students with <75% attendance

Trendline Analysis: Attendance movement across dates

Interactive Filters: Slice data by Department, Year, Subject, and Date

Clean Data Model: Fact table + two dimension tables for optimized querying

# Tech Stack

Power BI Desktop

Excel (ETL + dataset preparation)

DAX Measures for KPIs

Star Schema Data Modeling

# Project Highlights
✔ Data Cleaning & Prep

Processed raw attendance logs (150,000+ rows), added AttendanceFlag, removed duplicates, and structured data into analytical tables.

✔ Data Modeling

Fact table: attendance
Dimensions: student list, subject list
Relationships built on StudentID and SubjectCode to enable accurate filtering and drill-downs.

✔ DAX Measures

Total Classes

Present Count

Attendance %

At Risk classification

These metrics power all visuals in the dashboard.

✔ Insights

Identified subjects with consistently low attendance

Revealed attendance dips across specific dates

Highlighted student cohorts with risk of falling below required attendance thresholds

Enabled department-level and year-level analysis for targeted interventions

# Dashboard Views

Attendance Heatmap

Subject Performance Bar Chart

Attendance Trendline

At-Risk Student Table

Interactive department/subject/date filters

# Purpose

This dashboard simulates a real academic reporting system and demonstrates core data analyst skills:

Data transformation

Dimensional modeling

DAX calculation logic

Building actionable, business-relevant visuals

Delivering insights through interactive BI reports



*Author*
ROMA DSOUZA
Aspiring Data Analyst 
