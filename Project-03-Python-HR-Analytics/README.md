# Project 3: HR Analytics with Python

## 📊 Project Overview
Python-based analysis of employee attrition using Pandas, NumPy, and data visualization libraries to identify key factors driving employee turnover.

## 🎯 Objectives
- Analyze employee attrition patterns
- Identify departments and demographics at risk
- Discover salary and tenure correlations
- Provide data-driven HR recommendations

## 🛠️ Tools Used
- **Python 3** - Programming language
- **Pandas** - Data manipulation
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical graphics
- **Google Colab** - Development environment

## 📁 Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset (Kaggle)
- **Records:** 1,470 employees
- **Features:** 35 attributes
- **Target Variable:** Attrition (Yes/No)

## 📈 Key Findings

### Overall Attrition
- **Attrition Rate:** 16.12% (237 out of 1,470 employees)
- Significant employee turnover requiring intervention

### Department Analysis
- **Highest Attrition:** Sales department
- Department-specific retention strategies needed

### Salary Impact
- **Employees who left:** Average $4,787/month
- **Employees who stayed:** Average $6,833/month
- **Gap:** $2,046 monthly difference
- **Insight:** Low salary is major attrition driver

### Age Demographics
- **Employees who left:** Average age 33.6 years
- **Employees who stayed:** Average age 37.6 years
- **Insight:** Younger employees more likely to leave

### Tenure Patterns
- **Employees who left:** Average 5.1 years at company
- **Employees who stayed:** Average 7.4 years
- **Insight:** Early-tenure employees at higher risk

### Correlation Analysis
Top factors correlated with attrition:
1. Monthly Income (-0.16) - Lower salary = Higher attrition
2. Age (-0.16) - Younger = Higher attrition  
3. Years at Company (-0.13) - Less tenure = Higher attrition

## 🔍 Analysis Performed

1. **Data Exploration**
   - Dataset overview and structure
   - Missing value check (0 missing values)
   - Statistical summary

2. **Attrition Analysis**
   - Overall distribution
   - Department-wise breakdown
   - Demographic patterns

3. **Salary Analysis**
   - Income comparison by attrition status
   - Boxplot distributions

4. **Age Analysis**
   - Age distribution histograms
   - Comparative boxplots

5. **Tenure Analysis**
   - Years at company patterns
   - Attrition by experience level

6. **Correlation Analysis**
   - Heatmap of key variables
   - Attrition predictors identification

## 📂 Files
- `Project_3_HR_Analytics.ipynb` - Complete Jupyter Notebook with analysis
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` - Dataset
- `visualizations/` - All charts and graphs

## 💡 Skills Demonstrated
- Python programming
- Pandas data manipulation
- Statistical analysis
- Data visualization (Matplotlib, Seaborn)
- Business insights extraction
- Jupyter Notebook documentation

## 🚀 Business Recommendations

1. **Salary Adjustment:** Review compensation for employees earning below $5,000/month
2. **Early Career Focus:** Implement retention programs for employees with <5 years tenure
3. **Sales Department:** Investigate specific issues driving high attrition
4. **Young Talent:** Create engagement programs for employees under 35
5. **Competitive Compensation:** Bridge $2K salary gap to reduce turnover

## 📊 Future Analysis
- Predictive modeling for attrition risk
- Job satisfaction deeper analysis
- Work-life balance impact
- Performance rating correlation

---

**Completed:** 20.12.2025
**Environment:** Google Colab
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn
