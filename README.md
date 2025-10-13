# Impact of Tobacco on Blood Pressure & Heart Rate

This repository contains my undergraduate psychology research project analyzing the impact of tobacco use on blood pressure (BP) and heart rate (HR). The project demonstrates reproducible data analysis in R, with a focus on clear communication of results for both technical and non‑technical audiences.

---

## 📂 Repository Structure
- `data/dataset.csv` — raw dataset used in the analysis  
- `analysis/analysis.Rmd` — R Markdown file with full analysis and visualizations  
- `analysis/analysis.html` — knitted HTML report (viewable without R)  
- `figures/` — exported plots for quick reference  

---

## 📊 Results Preview

Here are a few key findings from the analysis:

![Blood Pressure by Smoking Status](figures/bp_by_status.png)  
*Mean systolic and diastolic BP by smoking status.*

![Heart Rate by Sex](figures/hr_by_sex.png)  
*Average heart rate differences by sex.*

---

## 🔎 Full Report
For the complete analysis, including descriptive statistics, ANOVAs, and discussion:

👉 [View the full HTML report](analysis/analysis.html)

---

## 🛠️ Reproducibility
To reproduce the analysis locally:

```r
# Install required packages
install.packages(c("tidyverse", "ggplot2"))

# Render the report
rmarkdown::render("analysis/analysis.Rmd")

```

---

## ✨ Skills Demonstrated
- Data wrangling and cleaning in R  
- Statistical testing (ANOVA, t‑tests)  
- Data visualization with ggplot2  
- Reproducible research practices  
- Clear communication of technical results  