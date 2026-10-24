**Hospital Patient Dashboard**

An interactive healthcare dashboard built natively inside Microsoft Excel to track operational KPIs, doctor workloads, and patient demographics across regional branches.

**Dashboard Preview**


**Project Structure**

_Worksheet: Dashboard_
Purpose: Main UI view
Key Data Fields: Interactive slicers, KPI metric cards, and charts

_Worksheet: Pivot Tables_
Purpose: Backend data engine
Key Data Fields: Summarized aggregation matrices powering the layout

_Worksheet: Patients_
Purpose: Patient log master
Key Data Fields: Patient_ID, Patient_Name, Gender, Age, Admission_Date, City

_Worksheet: Admissions_
Purpose: Real-time stay metrics
Key Data Fields: Admission_ID, Status (Admitted, Discharged, Under Treatment), Month

_Worksheet: Doctors_
Purpose: Personnel register
Key Data Fields: Doctor_ID, Doctor_Name, Experience_Years, Specialization

_Worksheet: Branches_
Purpose: Facility directory
Key Data Fields: Branch_ID, Branch_Name (Hyderabad, Vijayawada, Secunderabad, Visakhapatnam)

**Core Data Visualizations**

The dashboard tracks exactly 100 operational patient records:
• Patient Volume by Branch: Displays volumes across active clinics. Hyderabad Central has 26, Vijayawada City has 26, Secunderabad Square has 24, and Visakhapatnam Beach has 24.

• Monthly Admission Trends: Chronological line graph mapping volume variations. It peaked at 12 in July and holds steady at 5 from September to December.

• Case Distribution by Department: Evaluates operational volume per specialty. It is led by Pediatrics at 11 cases, while Cardiology, Neurology, and Orthopedics track 10 cases each.

• Physician Workload and Patient Status: Stacked breakdown monitoring individual caseload volumes and current treatment status per doctor.

• Male vs Female per Location: Highlights regional demographic splits. Hyderabad Central holds 22 female records, while Vijayawada City holds 24 male records.

• Overall Gender Breakdown: High-level dynamic donut chart reflecting the global gender split of 51% Male and 49% Female.

**Interactive Controls (Slicers)**

The application filters all interface metrics and visual components instantly using three control panels:
• Gender: Filters records by Male or Female demographics.

• City: Toggles active data across regions including Guntur, Hyderabad, Nellore, Secunderabad, Vijayawada, Visakhapatnam, and Vizag.

• Month: Filters timelines across specific monthly increments from January through December.

**Execution Instructions**

1. Download: Click on the main Excel workbook file (.xlsx) in this repository and select Download.
2. Open: Launch the workbook using the desktop version of Microsoft Excel.
3. Enable Content: Click Enable Editing or Enable Content at the top prompt to unlock the interactive data slicers and navigation links.
