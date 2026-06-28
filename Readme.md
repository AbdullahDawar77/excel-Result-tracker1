# 📊 Class Result Analysis Dashboard

An Excel-based student performance tracking system built for a **classroom of 30+ students**, analyzing results across **6 subjects** with an interactive dashboard, grade distribution, subject averages, and one-click navigation — all without any external tools or plugins.

---

## 🔍 Problem Statement

Teachers and school administrators often track student results in disconnected spreadsheets with no way to quickly identify top performers, struggling students, or subject-level weaknesses. This project solves that by building a fully structured Excel workbook that transforms raw marks data into a clear, navigable performance dashboard — ready for real classroom use.

---

## 📸 Screenshots

### 🏠 Home Navigation
![Home Navigation](Project%20Screenshots/Home-Navigation.png)

### 📊 Dashboard Overview
![Dashboard Overview](Project%20Screenshots/Dashboard.png)

### 📚 Subject Average
![Subject Average](Project%20Screenshots/Subject-Average.png)

### 🗃️ Cleaned Data
![Raw Data](Project%20Screenshots/Raw-Data.png)

---

## ⚙️ Process & Methodology

**1. Data Collection & Structuring**
- Recorded student names, roll numbers, and marks across 6 subjects: English, Urdu, Maths, Science, Islamiyat, and Tests.
- Structured data in a clean tabular format to support formula-driven analysis.

**2. Automated Calculations**
- Computed total marks, percentage, and grade per student using nested IF logic.
- Applied RANK function to generate dynamic student rankings without manual sorting.
- Used XLOOKUP for cross-sheet data retrieval between the raw data and analysis sheets.

**3. Class Metrics Summary**
- Calculated class-wide pass rate, failure rate, highest score, lowest score, and class average.
- Flagged top 5 and bottom 5 performers automatically using LARGE/SMALL functions.

**4. Grade Distribution Analysis**
- Categorized all students into grade bands (A–F) using COUNTIF-based logic.
- Displayed grade spread to help identify whether the class skewed high or low overall.

**5. Subject-Level Analysis**
- Computed average marks per subject to identify which subjects had the strongest and weakest performance.
- Enables teachers to spot curriculum gaps at a glance.

**6. Dashboard & Navigation Design**
- Built an interactive Home Page with hyperlink buttons for one-click sheet navigation.
- Added a Back to Home button on every sheet for seamless movement across the workbook.
- Applied conditional formatting to highlight grade bands and performance tiers visually.

---

## 📈 Key Findings

| Metric | Value |
|---|---|
| Total Students | 30+ |
| Subjects Tracked | 6 |
| Pass Rate | 100% |
| Failure Rate | 0% |
| Highest Score | 722 — Amir Nazir |
| Lowest Score | 284 — Qasim |
| Class Average | Calculated dynamically |

**Top 5 Performers:**
Amir Nazir · Touseef · Abid · Waqas · Adnan

**Bottom 5 Performers:**
Qasim · Talha · Seyab · Mosawer · Bihzad

> A 100% pass rate indicates strong overall class performance, but the 438-mark gap between the highest and lowest scorer points to significant variance worth addressing at the individual level.

---

## 🗂️ Workbook Structure

| Sheet | Description |
|---|---|
| Home | Navigation hub with hyperlink buttons to all sheets |
| Raw Data | Complete student records — marks, totals, grades, and status |
| Class Metrics | Pass/fail rate, class average, highest and lowest scores |
| Marks Analysis | Student rankings ordered by total marks |
| Grade Distribution | Count of students per grade band (A through F) |
| Subject Average | Per-subject average across the entire class |

---

## 🛠️ Excel Features Used

| Feature | Purpose |
|---|---|
| Nested IF Statements | Grade classification (A–F) based on percentage thresholds |
| RANK Function | Dynamic student ranking without manual sorting |
| XLOOKUP | Cross-sheet data retrieval for analysis sheets |
| COUNTIF / COUNTIFS | Grade distribution and pass/fail counting |
| LARGE / SMALL | Identifying top and bottom performers automatically |
| AVERAGE / MAX / MIN | Class-level and subject-level summary statistics |
| Conditional Formatting | Visual highlighting of grade bands and performance tiers |
| Hyperlinks | One-click navigation between all worksheets |
| Dashboard Design | Structured layout for non-technical users (teachers, admin) |

---

## 📁 Repository Structure

```
Class-Result-Analysis-Dashboard/
│
├── Project Screenshots/
│   ├── Home-Navigation.png       # Home page with navigation buttons
│   ├── Dashboard.png             # Main class performance dashboard
│   ├── Subject-Average.png       # Subject-wise average analysis
│   └── Raw-Data.png              # Cleaned student marks data
│
├── Excel-Result-Tracker.xlsx     # Main workbook with all sheets and dashboard
├── Raw-DataSet.csv               # Raw dataset for use in other tools
└── README.md
```

---

## ▶️ How to Use

1. Download or clone this repository.
2. Open `Excel-Result-Tracker.xlsx` in Microsoft Excel.
3. Start on the **Home** sheet and use the navigation buttons to explore each section.
4. The **Raw Data** sheet is the source — all other sheets pull from it automatically.
5. To adapt for a new class, update the Raw Data sheet and all formulas recalculate instantly.
6. Use `Raw-DataSet.csv` to import the dataset into Python, SQL, or Power BI for extended analysis.

---

## 💡 Business & Classroom Value

1. **Instant performance snapshot** — teachers can identify struggling students without manually scanning rows of marks.
2. **Subject gap detection** — subject averages reveal which topics need more classroom attention before the next assessment.
3. **Reusable template** — replacing student data auto-updates every metric, ranking, and chart — no rebuilding required each term.
4. **Portfolio-ready** — demonstrates real-world Excel skills applicable to MIS Analyst, Reporting Analyst, and Data Analyst roles.

---

## 🔮 Future Enhancements

- Add **Pivot Table-based slicers** for dynamic filtering by grade or subject.
- Build a **Power BI version** of the dashboard for interactive web-based reporting.
- Introduce **trend analysis** across multiple terms to track student progress over time.
- Add a **printable report card** sheet auto-populated from the raw data.
- Connect to a **SQL database** for multi-class or multi-school scalability.

---

## 👤 Author

**Abdullah Dawar**
Aspiring Data Analyst | Excel • SQL • Power BI
[GitHub Profile](https://github.com/AbdullahDawar77)

---

*This project is part of a data analytics portfolio developed to demonstrate real-world data analysis skills for analyst roles.*
