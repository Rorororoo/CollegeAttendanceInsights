# CollegeAttendanceInsights
College Attendance Insights Dashboard

A fully interactive Power BI dashboard analyzing student attendance across 12 subjects for 500+ students over one month.
The project identifies at-risk students, subjects with low turnout, trends over time, and department-level patterns.

Features

✔ Heatmap of attendance by student & subject
✔ Average attendance % per subject
✔ Attendance trendline across dates
✔ At-risk student identification using DAX
✔ Interactive slicers for Department, Year, Subject & Date
✔ Clean data model with star schema
✔ Fully dynamic visuals connected through relationships

Tech Used

Power BI Desktop

Excel (datasets)

DAX (calculated measures)

 Data Model

attendance (fact table)

student list (dimension)

subject list (dimension)

Relationships:

StudentID (1 → *)

SubjectCode (1 → *)

 Key Insights

Avg attendance across subjects: ~78%

Subjects with lowest turnout are clearly highlighted


Consistent trends detected across different dates

At-risk students (attendance < 75%) automatically flagged
