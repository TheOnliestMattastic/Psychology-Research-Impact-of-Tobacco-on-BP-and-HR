# Impact of Tobacco on Blood Pressure & Heart Rate

This repository contains my undergraduate psychology research project analyzing the impact of tobacco use on blood pressure (BP) and heart rate (HR).  
It demonstrates **end-to-end data analysis in R** — from cleaning and structuring raw data, to performing statistical tests, to presenting results in a clear, reproducible format.  

Originally completed as an academic study, I’ve rebuilt and documented it here to showcase the **technical, analytical, and communication skills** I bring to IT and data-driven roles.

---

## 🚀 Project Highlights
- **Reproducible workflow**: Analysis scripted in R Markdown and published as an HTML report.  
- **Statistical rigor**: ANOVA and post-hoc testing to evaluate group differences.  
- **Data visualization**: Publication-quality plots created with `ggplot2`.  
- **Communication**: Results presented for both technical and non-technical audiences.  
- **Version control**: Organized repo structure with Git/GitHub for transparency and collaboration.  

---

## 📂 Repository Structure
- `data/dataset.csv` — raw dataset used in the analysis  
- `analysis/analysis.Rmd` — full R Markdown analysis  
- `docs/analysis.html` — knitted HTML report (viewable without R)  
- `docs/figures/` — exported plots for quick reference  
- `Impact_of_Tobacco_Consumption_on_BP_and_HR.pdf` — full research paper  

---

## 📊 Key Findings
- **Blood Pressure**: Heavy smokers exhibited significantly higher systolic BP compared to moderate smokers.  
- **Diastolic BP**: Differences approached significance, suggesting possible dose effects.  
- **Heart Rate**: No overall group differences, but moderate-smoking women showed slightly higher HR than men.  
- **Gender Effects**: Female heavy smokers had higher SBP than female moderates.  

Example visualizations:

![Blood Pressure by Smoking Status](docs/figures/bp_by_status.png)  
*Mean systolic and diastolic BP by smoking intensity.*

![Heart Rate by Sex](docs/figures/hr_by_sex.png)  
*Average HR differences by sex.*

---

## 🔎 Full Report
- 👉 [View the complete HTML report](docs/analysis.html)  
- 👉 [Download the full research paper (PDF)](Impact_of_Tobacco_Consumption_on_BP_and_HR.pdf)   

---

## 🛠️ Reproducibility
To reproduce the analysis locally:

```r
# Install required packages
install.packages(c("tidyverse", "ggplot2", "rmarkdown, DescTools"))

# Render the report
rmarkdown::render("analysis/analysis.Rmd")
```

---

## 💡 Skills Demonstrated
- Data wrangling and cleaning in R  
- Statistical testing (ANOVA, t‑tests, post‑hoc comparisons)  
- Data visualization with ggplot2  
- Reproducible research practices (R Markdown, GitHub Pages)  
- Clear, structured communication of technical results  
- Professional documentation and version control with Git/GitHub  

---

## 🎯 Why This Matters for Recruiters
This project highlights my ability to:
- Translate raw data into actionable insights.  
- Build reproducible workflows that others can follow.  
- Communicate findings clearly to both technical and non‑technical stakeholders.  
- Apply strong documentation and version control practices — skills directly transferable to IT support, data analysis, and technical communication roles.  