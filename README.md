
#  Student Performance and Aptitude Analysis
A comprehensive statistical analysis validating course placement effectiveness at The Key English Course Company

<p align="center">
  <img src="./assets/logo.png" alt="The Key" width="200" />
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

## 🛠 Methodology & Data
| Category | Details |
| :--- | :--- |
| **Sample Size** | 150 Students |
| **Course Levels** | Advanced, Intermediate, Foundation |
| **Key Metrics** | Aptitude Scores, Final Performance Grades |
| **Statistical Methods** | [e.g., ANOVA, Pearson Correlation, Regression Analysis] |

---

.
├── README.md                        # This file
├── assets                           # Complete Jupyter notebook with all calculations/
│   └── logo.jpg                     # company logo         
├── analysis_notebook.ipynb          # analysis report        
├── report in progress.pdf           # analysis report
└── requirements.txt                 # Python dependencies

## 📊 Research Results & Analysis

The following analysis was conducted using Python (Pandas, Scipy, Seaborn) to evaluate the effectiveness of the placement system.

### 1. Enrollment & Performance Patterns 📈
The data shows a clear stratification of performance based on course levels, confirming that "The Key" system effectively groups students of similar abilities.

| Course Level | Avg. Performance Score |
| :--- | :---: |
| **Advanced** | 3.239 |
| **Intermediate** | 2.518 |
| **Foundation** | 1.865 |

### 2. Statistical Validation (ANOVA) 🧠
* **ANOVA p-value:** `0.0000`
* **Interpretation:** Because the p-value is near zero, we can state with high confidence that there are **statistically significant differences** in aptitude scores across the three course levels. This validates that the placement thresholds are not arbitrary but reflect genuine differences in student readiness.

### 3. Aptitude vs. Performance Correlation 🔗
* **Pearson Correlation Coefficient:** `0.89`
* **Interpretation:** There is a **very strong positive correlation** between initial aptitude scores and final performance. This suggests the placement test is a highly reliable predictor of academic success.

---

## 💡 Strategic Implications & Quality Assessment

Based on the statistical output, the following conclusions have been drawn:

* **High Placement Accuracy:** The strong correlation (0.89) proves that "The Key" placement process successfully matches students to environments where they can succeed. High-aptitude students are consistently reaching high-performance targets.
* **Program Differentiation:** The distinct performance gaps between levels (Advanced vs. Foundation) indicate that the curriculum is well-tailored. The program successfully differentiates learning outcomes, ensuring that Foundation students are not overwhelmed and Advanced students are sufficiently challenged.
* **Quality Assurance:** These results serve as a "Green Light" for the current system. The data supports the continued use of the existing aptitude test as a primary filter for course enrollment.

---

## 🖼️ Visualizations
![Analysis Results](https://raw.githubusercontent.com/fakhrzakbar/Project--/main/Result.png)
