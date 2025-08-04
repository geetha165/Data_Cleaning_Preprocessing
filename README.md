# 🧹 Data Cleaning and Preprocessing Summary: Medical Appointment No Show Dataset

## 📂 Cleaned Dataset

**Filename(s):**
- `Medical_Appointment_Cleaned.csv`
- `medical_appointment_no_shows_csv`

These files represent the raw dataset after cleaning and minor preprocessing using **Microsoft Excel**.

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


