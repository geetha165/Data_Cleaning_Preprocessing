# 🧹 Data Cleaning Summary: Medical Appointment No Show Dataset

## 📂 Cleaned Dataset
**Filename(s):**
- `Medical_Appointment_NoShow_Cleaned.xlsx`
- `Medical_Appointment_NoShow_Cleaned_WithExtras.xlsx`

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

## 📌 Notes
- Two cleaned versions are saved:
  - One with only cleaned original fields.
  - Another with **additional derived columns** like `Scheduled_Date`, `Appointment_Time`, and `Age_Group`.
- Data cleaning was performed using **Microsoft Excel 2016+** with filters, formulas, and formatting tools.

---

## 📁 Files Included
- `Medical_Appointment_NoShow_Cleaned.xlsx`
- `Medical_Appointment_NoShow_Cleaned_WithExtras.xlsx`
- `README.md` (this file)

---

## 📈 Next Steps (Optional)
You can now perform:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Predictive Modeling (No-show prediction)

---

## 👩‍💻 Author
**Geetha V**  
M.Sc. Computer Science  
Aspiring Data Analyst  
