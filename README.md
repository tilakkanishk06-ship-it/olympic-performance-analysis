# Global Olympic Sports Performance Analysis (1992–2026)

Skill Wallet Data Analytics – Tableau Virtual Internship Project.

## Overview
This repository analyzes historical Olympic performance from 1992 to 2026 across medal counts, regional efficiency, and national sports investments.

## Tableau Calculated Fields
- **Average Medals per Athlete**: `SUM([Total Medals]) / COUNTD([Athlete ID])`
- **Medal Efficiency Percentage**: `(SUM([Total Medals]) / SUM([Sports Investment])) * 100`

## Repository Structure
- `data/`: CSV datasets for athletes, medal results, and sports investment.
- `tableau/`: Tableau workbook configurations.
- `index.html`: Interactive web demo for GitHub Pages.
