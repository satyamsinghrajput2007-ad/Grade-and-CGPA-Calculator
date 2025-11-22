# 📊 Grade & CGPA Calculator (Python • NumPy • Pandas)

This project is a *Grade and CGPA (Cumulative Grade Point Average) Calculator* built using *Pandas* and *NumPy*.  
It reads student marks from an Excel/CSV file, calculates the *grade* for each subject, converts grades into *grade points, computes the **CGPA*, and finally exports the updated result back into a new Excel file.

---

## 🚀 Features

- ✔ Reads data from Excel or CSV  
- ✔ Calculates grades based on marks  
- ✔ Converts grades (S, A, B, C…) into grade points  
- ✔ Computes CGPA using weighted credits  
- ✔ Rounds off CGPA to 2 decimal places  
- ✔ Uses Pandas + NumPy for fast computation  

---

## 📘 Grade System Used

| Grade | Point |
|-------|--------|
| S     | 10     |
| A     | 9      |
| B     | 8      |
| C     | 7      |
| D     | 6      |
| E     | 5      |
| F     | 0      |

---

## 🧮 CGPA Formula

\[
\text{CGPA} = \frac{\sum (\text{Grade Point} \times \text{Credit})}{\text{Total Credits}}
\]

Example:  
If a student gets A in a 4-credit course,  
Grade Point = 9  
Weighted = 9 × 4 = 36

---

## 🛠 Technologies Used

- *Python 3*
- *Pandas* (data handling)
- *NumPy* (numerical operations)
- *OpenPyXL* (Excel exporting + coloring)

---

## 📂 File Structure
