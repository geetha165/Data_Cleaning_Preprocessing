# 🧹 Data Cleaning and Preprocessing Summary: Medical Appointment No Show Dataset

This project focuses on cleaning and preparing the **Medical Appointment No Show** dataset for analysis. The dataset records patient appointment details and whether they attended or missed their appointment.

---

📂 **Project Files**

- `medical_appointment_no_shows.csv` – Raw dataset with original records  
- `Medical_Appointment_Cleaned.csv` – Cleaned and preprocessed dataset ready for analysis  

---

## 🛠️ Summary of Cleaning Steps

| Step | Description |
|------|-------------|
| ✅ | **Renamed columns** for clarity (e.g., `PatientId` → `Patient_Id`) and removed spaces. |
| ✅ | **Split datetime columns** into separate Date and Time fields for both Scheduled and Appointment dates. |
| ✅ | **Created `Age_Group` column** based on age: `Adolescent`, `Middle Age`, `Old`. |
| ✅ | **Handled age issues**: removed rows with age = -1, but retained age = 0 for further analysis. |
| ✅ | **Standardized text** values (e.g., converted `Gender` to `Male/Female`, `Neighbourhood` to Title Case). |
| ✅ | **Removed duplicate records** using Excel’s “Remove Duplicates” function. |
| ✅ | **Checked and confirmed binary values** (e.g., `Diabetes`, `Hypertension`, `Handicap`, etc.). |
| ✅ | **Verified data types**: ensured numeric columns are correct, and dates are in proper `dd/mm/yyyy` format. |
| ✅ | **Checked for missing values** using filters and removed any empty rows/columns if found. |

---

🧼 **Data Cleaning Tasks**

- Removed duplicate records  
- Handled invalid age values (e.g., -1), preserved 0 due to high occurrence  
- Standardized categorical text (e.g., gender casing, neighborhood formatting)  
- Separated and formatted datetime fields (`Scheduled_Day`, `Appointment_Day`)  
- Ensured correct data types (e.g., age as integer, date as datetime)  
- Renamed columns for readability (e.g., no spaces, consistent naming)  

---

📊 **Cleaning Highlights**

- Created a new `Age_Group` column based on age  
- Reviewed `Handicap` values and ensured validity (0 to 4)  
- Ensured consistency in "No-show" column values  
- Verified large-volume fields like `Neighbourhood` for casing issues  
- Retained medically significant zero values in age and other features  

---

🛠 **Tools Used**

- **Microsoft Excel** – Data filtering, formula-based transformation, manual checks  
- **CSV Format** – Easy integration into Python, SQL, or BI tools for future use  

---

✅ **Final Conclusion**

This data cleaning process transformed raw medical appointment records into a consistent and analysis-ready dataset. This cleaned version can now be used for:

- No-show prediction modeling  
- Patient behavior analysis  
- Visualizing medical service usage patterns  

The cleaned dataset ensures accurate and reliable results for any downstream data analysis.

---










