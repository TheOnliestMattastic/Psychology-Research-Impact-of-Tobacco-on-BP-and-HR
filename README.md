```
___________.__             ________         .__  .__                 __   
\__    ___/|  |__   ____   \_____  \   ____ |  | |__| ____   _______/  |_ 
  |    |   |  |  \_/ __ \   /   |   \ /    \|  | |  |/ __ \ /  ___/\   __\
  |    |   |   Y  \  ___/  /    |    \   |  \  |_|  \  ___/ \___ \  |  |  
  |____|   |___|  /\___  > \_______  /___|  /____/__|\___  >____  > |__|  
                \/     \/          \/     \/             \/     \/        
   _____          __    __                   __  .__                      
  /     \ _____ _/  |__/  |______    _______/  |_|__| ____                
 /  \ /  \\__  \\   __\   __\__  \  /  ___/\   __\  |/ ___\               
/    Y    \/ __ \|  |  |  |  / __ \_\___ \  |  | |  \  \___               
\____|__  (____  /__|  |__| (____  /____  > |__| |__|\___  >              
        \/     \/                \/     \/               \/               
```

# 📊 Impact of Tobacco on Blood Pressure & Heart Rate  
_A reproducible research project turning raw data into clear insights._

<!-- Badges -->
[![Live Report](https://img.shields.io/badge/Report-Live_Site-bd93f9?style=for-the-badge&logo=githubpages&logoColor=white&labelColor=6272a4)](https://theonliestmattastic.github.io/Psychology-Research-Impact-of-Tobacco-on-BP-and-HR/)
[![View Full Analysis](https://img.shields.io/badge/R_Analysis-Full_Report-bd93f9?style=for-the-badge&logo=r&logoColor=white&labelColor=6272a4)](https://theonliestmattastic.github.io/Psychology-Research-Impact-of-Tobacco-on-BP-and-HR/analysis.html)
![License](https://img.shields.io/badge/License-CC0--1.0-bd93f9?style=for-the-badge&logo=creativecommons&logoColor=white&labelColor=6272a4)  
[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-bd93f9?style=for-the-badge&logo=githubpages&logoColor=white&labelColor=6272a4)](https://theonliestmattastic.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-bd93f9?style=for-the-badge&logo=github&logoColor=white&labelColor=6272a4)](https://github.com/theonliestmattastic)

## 🔭 Overview
This repository contains my **undergraduate psychology research project** analyzing the impact of tobacco use on blood pressure (BP) and heart rate (HR).  

It demonstrates **end-to-end data analysis in R** — from cleaning and structuring raw data, to running statistical tests, to publishing results in a clear, reproducible format.  

Originally completed as an academic study, I’ve rebuilt and documented it here to highlight my **technical, analytical, and communication skills** that transfer directly into IT support, automation, and data-driven roles.

## 🛰️ Tech Stack
[![R](https://img.shields.io/badge/Language-R-bd93f9?style=for-the-badge&logo=r&logoColor=white&labelColor=6272a4)](https://www.r-project.org/)
[![RMarkdown](https://img.shields.io/badge/Docs-RMarkdown-bd93f9?style=for-the-badge&logo=rstudioide&logoColor=white&labelColor=6272a4)](https://rmarkdown.rstudio.com/)
[![Tidyverse](https://img.shields.io/badge/Library-Tidyverse-bd93f9?style=for-the-badge&logo=tidyverse&logoColor=white&labelColor=6272a4)](https://www.tidyverse.org/)
[![ggplot2](https://img.shields.io/badge/Visualization-ggplot2-bd93f9?style=for-the-badge&logo=tidyverse&logoColor=white&labelColor=6272a4)](https://ggplot2.tidyverse.org/)
[![DescTools](https://img.shields.io/badge/Package-DescTools-bd93f9?style=for-the-badge&logo=r&logoColor=white&labelColor=6272a4)](https://cran.r-project.org/web/packages/DescTools/index.html)

## ☄️ Features
- ✅ **Reproducible workflow** scripted in R Markdown  
- ✅ **Statistical rigor**: ANOVA + post‑hoc testing  
- ✅ **Data visualization** with publication‑quality plots (`ggplot2`)  
- ✅ **Clear communication** for both technical and non‑technical audiences  
- ✅ **Version control** with Git/GitHub for transparency  

## 🚀 Getting Started
### Prerequisites
- [R](https://www.r-project.org/) (≥ 4.0)  
- R packages: `tidyverse`, `ggplot2`, `rmarkdown`, `DescTools`  

### Installation
```bash
git clone https://github.com/TheOnliestMattastic/Psychology-Research-Impact-of-Tobacco-on-BP-and-HR.git
cd Psychology-Research-Impact-of-Tobacco-on-BP-and-HR
```

### Usage
```r
# Install required packages
install.packages(c("tidyverse", "ggplot2", "rmarkdown", "DescTools"))

# Render the report
rmarkdown::render("analysis/analysis.Rmd")
```

## 🗺️ Repo Structure
```plaintext
├── data/
│   └── dataset.csv                # Raw dataset
├── analysis/
│   └── analysis.Rmd               # Full R Markdown analysis
├── docs/
│   ├── analysis.html              # Knitted HTML report
│   └── figures/                   # Exported plots
├── Impact_of_Tobacco_Consumption_on_BP_and_HR.pdf  # Full research paper
└── README.md
```

## 🔬 Key Findings
- **Systolic BP:** Heavy smokers > moderate smokers (significant)  
- **Diastolic BP:** Near‑significant differences, suggesting dose effects  
- **Heart Rate:** No overall group differences, but moderate‑smoking women > men  
- **Gender Effects:** Female heavy smokers > female moderates in SBP  

Example visualizations:  

![Blood Pressure by Smoking Status](docs/figures/bp_by_status.png)  
*Mean systolic and diastolic BP by smoking intensity.*  

![Heart Rate by Sex](docs/figures/hr_by_sex.png)  
*Average HR differences by sex.*  

## 📡 Lessons Learned
- Built confidence in **reproducible research workflows**  
- Strengthened **data visualization and statistical testing** skills  
- Practiced **clear documentation** for both academic and technical audiences  
- Reinforced habits of **version control and transparency**  

## 🛸 License

This project is licensed under the [CC0‑1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/).

## 🪐 Why This Matters for Recruiters
This project shows I can:  
- Translate **raw data into actionable insights**  
- Build **reproducible, documented workflows**  
- Communicate results to **diverse audiences**  
- Apply **rigorous documentation and GitHub practices**  

## 👽 Contact!

Curious about my projects? Want to collaborate or hire for entry-level IT/support/dev roles?
Shoot me an email or connect on GitHub—I reply quickly and love new challenges.  

[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-bd93f9?style=for-the-badge&logo=githubpages&logoColor=white&labelColor=6272a4)](https://theonliestmattastic.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-bd93f9?style=for-the-badge&logo=github&logoColor=white&labelColor=6272a4)](https://github.com/theonliestmattastic)
[![Email](https://img.shields.io/badge/Email-matthew.poole485%40gmail.com-bd93f9?style=for-the-badge&logo=gmail&logoColor=white&labelColor=6272a4)](mailto:matthew.poole485@gmail.com)  

> _“Sometimes the questions are complicated and the answers are simple.”_ — Dr. Seuss