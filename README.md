Data Analytics Internship – Task 01

Task: Data Cleaning and Preprocessing

📌 Objective

The goal of this task is to clean and preprocess a raw dataset by handling missing values, duplicates, inconsistent formats, and incorrect data types.

📊 Dataset

Name: Medical Appointment No Shows (Kaggle)

Description: Contains information about patients’ medical appointments and whether they showed up or not.

🛠 Tools Used

Python (Pandas, NumPy)

Jupyter Notebook

🔎 Steps Performed

Loaded the dataset and inspected rows, columns, and data types.

Checked and handled missing values using dropna() / fillna().

Removed duplicate rows with .drop_duplicates().

Converted date columns (ScheduledDay, AppointmentDay) to datetime format.

Fixed data inconsistencies:

Standardized gender values.

Saved the cleaned dataset as cleaned_medical_appointments.csv.

📂 Deliverables

Raw dataset (original).

Cleaned dataset (cleaned_medical_appointments.csv).

Notebook/Script (task01_cleaning.ipynb).

✅ Outcome

A structured, clean dataset ready for further analysis and visualization.
