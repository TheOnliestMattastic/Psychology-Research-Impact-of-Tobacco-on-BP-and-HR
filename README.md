# Psychology Research: Impact of Tobacco Consumption on Blood Pressure and Heart Rate

_A reproducible analysis of the effects of smoking status on blood pressure and heart rate in adults._

## Overview

This repository contains the code, data, and documentation for a longitudinal study analyzing the impact of tobacco consumption on blood pressure (BP) and heart rate (HR). The study uses a subset of the Framingham Heart Study dataset and focuses on differences in cardiovascular parameters among adult smokers categorized by smoking frequency.

**Research Paper:**  
Matthew Poole Chicano  
Department of Psychology, City College of New York  
PSY 32100: Experimental Psychology  
Dr. Sophia Barrett  
August 2, 2022

## Introduction

Cardiovascular diseases (CVDs) are the leading cause of preventable deaths globally. Both hypertension and tobacco use are major risk factors for CVD. While the acute effects of smoking on HR and BP are well-documented, the long-term impact remains unclear and is subject to conflicting results in the literature.

In this study, I investigate the relationship between cigarette smoking and blood pressure across varying smoking frequencies. Specifically, I hypothesize that individuals who smoke more than 5 cigarettes per day will exhibit higher systolic BP (SBP), diastolic BP (DBP), and HR compared to those who smoke only 1 to 5 cigarettes per day.

## Methods

- **Participants:**  
  Subset of Framingham Heart Study data (n = 780, ages 44–80, 51.28% female). Only self-identified smokers included.
  - Groups:  
    - Light: 1–5 cigarettes/day  
    - Moderate: 6–20 cigarettes/day  
    - Heavy: 21+ cigarettes/day

- **Data Source:**  
  Framingham Heart Study (observational, biennial health exams, 1948–present).

- **Analysis:**  
  - One-way ANOVA to compare SBP, DBP, and HR across smoking groups
  - Subgroup analyses by sex
  - T-tests for sex-based differences within smoking groups

## Results

- **SBP:** Heavy smokers had significantly higher SBP than moderate smokers.
- **DBP:** Heavy smokers showed a trend toward higher DBP than moderate smokers (significant at 90% confidence).
- **HR:** No significant differences detected between groups.
- **Sex Differences:**  
  - Female heavy smokers exhibited higher SBP than moderate female smokers.
  - Moderate female smokers had higher HR than moderate male smokers.

The hypothesis was not fully supported: while SBP and DBP were higher in heavy versus moderate smokers, there were no significant differences between light and heavier smokers.

## Discussion

- The study found elevated BP in heavy smokers compared to moderate smokers, with some trends varying by sex.
- No significant differences were found between light and heavy smokers, suggesting that other factors (age, BMI, family history) may influence outcomes.
- The lack of significant HR differences and the moderate confidence interval for DBP highlight the complexity of the smoking-BP relationship.
- The results emphasize the need for targeted interventions for heavy smokers and further research controlling for additional confounding variables.

## Repository Contents

- `analysis/`: Code for statistical analysis and data processing
- `data/`: Cleaned dataset (subset of Framingham Heart Study)
- `paper/`: Research paper and supporting documentation
- `figures/`: Generated plots and charts

## Usage

1. **Clone the repository:**
    ```sh
    git clone https://github.com/TheOnliestMattastic/Psychology-Research-Impact-of-Tobacco-on-BP-and-HR.git
    cd Psychology-Research-Impact-of-Tobacco-on-BP-and-HR
    ```
2. **Review the research paper** in `paper/` for study details.
3. **Run analysis scripts** in `analysis/` using your preferred statistical software.

## License

This project is licensed under the [CC0-1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.

## Author

- [Matthew Poole Chicano](https://github.com/TheOnliestMattastic)

## Repository

- [GitHub Repository](https://github.com/TheOnliestMattastic/Psychology-Research-Impact-of-Tobacco-on-BP-and-HR)
