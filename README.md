
#  Student Performance and Aptitude Analysis
A comprehensive statistical analysis validating course placement effectiveness at The Key English Course Company

<p align="center">
  <img src="https://raw.githubusercontent.com/fakhrzakbar/Project--/main/Assets/logo.png" width="300" alt="Project Logo">
</p>

---

## 📝 Project Overview
This project presents a **rigorous statistical analysis** of 150 students across three distinct English course levels. The primary goal is to validate the accuracy and effectiveness of **The Key’s** course placement system.

> [!IMPORTANT]
> **Objective:** To examine the relationship between initial aptitude test scores and actual classroom performance, ensuring students are placed in the optimal learning environment for their skill level.

---

## 🔍 Research Questions
The study is structured around four core inquiries:

1. **Enrollment Patterns** 📊
   * Do students with different performance levels enroll in different course levels?
2. **Aptitude Variance** 🧠
   * Are there significant differences in aptitude scores across course levels?
3. **Performance Correlation** 📈
   * What is the correlation between aptitude scores and actual performance?
4. **Strategic Implications** 💡
   * What are the implications for course placement and overall program quality?


---

## 📂 Repository Contents

```text
.
├── README.md                        # Project documentation and summary
├── Assets/                          # Folder for visual elements
│   └── logo.png                     # Company logo
├── analysis_notebook.ipynb          # Jupyter notebook with full calculations
├── report in progress.pdf           # Detailed analysis report (PDF)
└── requirements.txt                 # Python dependencies
```

---

# Dataset Description

### Sample Characteristics
* **Total Students:** 150
* **Sample Distribution:** 50 students per course level
* **Sampling Method:** Stratified random sampling
* **Data Completeness:** No missing values

### Variables

| Variable | Type | Description | Range |
| :--- | :--- | :--- | :--- |
| **`student_id`** | Integer | Unique student identifier | 1-150 |
| **`course_level`** | Categorical | Course enrollment level | Advanced, Intermediate, Foundation |
| **`performance_score`** | Float | Academic achievement score | 1.55 - 3.80 (4-point scale) |
| **`aptitude_score`** | Integer | Language aptitude test score | 9 - 97 (max 126) |

# Key Results Summary

### Descriptive Statistics

| Level | Performance Mean | Performance SD | Aptitude Mean | Aptitude SD |
| :--- | :--- | :--- | :--- | :--- |
| **Advanced** | 3.239 | 0.384 | 67.46 | 19.17 |
| **Intermediate** | 2.518 | 0.392 | 42.74 | 18.28 |
| **Foundation** | 1.865 | 0.177 | 22.52 | 7.03 |

### ANOVA Results

| Variable | F-statistic | df | p-value | η² (Effect Size) |
| :--- | :--- | :--- | :--- | :--- |
| **Performance** | 213.43 | (2, 147) | < 0.001*** | 0.744 (Large) |
| **Aptitude** | 101.17 | (2, 147) | < 0.001*** | 0.579 (Large) |

### Correlation

| Relationship | r | p-value | Interpretation |
| :--- | :--- | :--- | :--- |
| **Performance → Aptitude** | 0.887 | < 0.001*** | Very Strong Positive |

# Notebook Structure

The Jupyter notebook (`analysis_notebook.ipynb`) mirrors the PDF report and includes:

1. **Chapter 1:** Introduction & Data Loading
2. **Chapter 2:** Data Overview & Quality Checks
3. **Chapter 3:** Descriptive Statistics
4. **Chapter 4:** Assumption Testing
5. **Chapter 5:** ANOVA Analysis
6. **Chapter 6:** Post-Hoc Tests
7. **Chapter 7:** Correlation Analysis
8. **Chapter 8:** Effect Sizes
9. **Chapter 9:** Visualizations
10. **Chapter 10:** Summary & Conclusions

**Each chapter includes:**
- [x] Complete Python code
- [x] Detailed explanations
- [x] Statistical interpretations
- [x] Visualization outputs
- [x] Result verification

# Documentation

See [detailed_report.pdf](https://github.com/fakhrzakbar/Project-The-Key-English-Course/blob/main/detailed_report.pdf) for the full 50-page analysis report with:

* Executive summary
* Detailed methodology
* Comprehensive results
* Practical recommendations
* Glossary of terms
