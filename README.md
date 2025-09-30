# 📊 YouTube Users by Country – Statistical Analysis

![YouTube](https://img.shields.io/badge/YouTube-Data_Analysis-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
![Statistical Analysis](https://img.shields.io/badge/Statistical_Analysis-R_Excel-007ACC?style=for-the-badge&logo=r&logoColor=white)

---

## 📖 Project Overview
This project presents a **comprehensive statistical analysis** of YouTube user distribution across **87 countries** worldwide.  
The study applies descriptive statistics, confidence intervals, hypothesis testing, and outlier detection to uncover adoption trends and patterns that matter to content creators and market analysts. **This is my academical work**.

---

## 🎯 Key Objectives
- Analyze YouTube user penetration across countries  
- Calculate confidence intervals for population parameters  
- Perform hypothesis testing on adoption rates  
- Detect outliers and analyze distribution skewness  
- Provide insights for digital creators and analysts  

---

## 📊 Dataset Information
- **Total Countries:** 87  
- **Mean YouTube Users:** 66.03%  
- **Standard Deviation:** 19.06  
- **Range:** 13.83% – 98.49%  
- **Distribution Shape:** Left-skewed (–1.13)  

---

## 🔍 Statistical Analysis Performed
### Descriptive Statistics
- Summary of adoption rates  
- Central tendency & variability  

### Confidence Interval Analysis
| Confidence Level | Mean Interval     | Variance Interval   | Std. Deviation Interval |
|------------------|------------------|---------------------|-------------------------|
| 95%              | (61.97, 70.09)   | (275.25, 502.15)    | (16.59, 22.41)          |
| 98%              | (61.19, 70.87)   | (261.72, 534.64)    | (16.18, 23.12)          |

### Sample Analysis (10 Countries)
Countries: India, USA, Brazil, Indonesia, Mexico, Japan, Pakistan, Germany, Vietnam, Turkey  
- **Sample Mean:** 59.72%  
- **95% CI:** (48.27, 71.15)  
- **98% CI:** (45.44, 73.98)  

---

## 📈 Key Findings
### Distribution Insights
- YouTube adoption shows **left-skewness**  
- Most countries cluster at higher adoption levels  
- Lower-adoption outliers identified  

### Outlier Detection (Low Adoption Countries)
- Nigeria (13.83%)  
- Kenya (18.20%)  
- Philippines (19.49%)  
- Bangladesh (20.42%)  
- Ghana (20.13%)  
- Senegal (20.65%)  

### Hypothesis Testing
**Test:** Population Mean vs Lower Quartile (Q1 = 57.17)  
- T-statistic: 0.04985  
- P-value: 0.96036  
- **Conclusion:** Fail to reject null hypothesis  
- **Interpretation:** No significant difference between mean and Q1  

---

## 🛠️ Technical Implementation
### Tools & Technologies
- **Data Handling:** Google Sheets
- **Statistical Computing:** XLMiner Analysis ToolPak
- **Visualization:** Google Sheets
- **Documentation:** Word 

### Statistical Methods Applied
- Descriptive Statistics  
- Confidence Interval Estimation  
- Hypothesis Testing (t-test)  
- Outlier Detection (IQR Method)  
- Distribution & Variance Analysis  

---

## 💡 Business Implications
### For Content Creators
- Identify high-penetration regions for targeted strategies  
- Optimize content distribution based on audience size  

### For Market Analysts
- Track **digital platform adoption trends**  
- Benchmark regions against global averages  
- Detect emerging growth markets  

---

## 🚀 Getting Started
### Prerequisites
- [R / RStudio](https://posit.co/download/rstudio-desktop/)  
- Excel or Google Sheets  
- Basic statistics knowledge  
