Hospital Data Analysis Dashboard (Power BI Project)
📊 Project Overview

This project analyzes hospital data using Microsoft Power BI to uncover insights about patient demographics, admissions trends, and department performance.
The goal is to help hospital management improve operational efficiency and patient care through data-driven decision-making.

📁 Dataset Information
1️⃣ Patients Table
Column	Description
PatientID	Unique patient identifier
Name	Full name
Age	Patient’s age
Gender	Male / Female
City	Patient’s city
2️⃣ Admissions Table
Column	Description
AdmissionID	Unique admission identifier
PatientID	Linked to Patients table
Department	Hospital department name
DateAdmitted	Admission date
DateDischarged	Discharge date
🧩 Data Model

The data model includes relationships between:

Patients → Admissions (1 to many)

Calendar → Admissions (1 to many on DateAdmitted)
