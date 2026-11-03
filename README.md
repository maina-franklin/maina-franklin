# Kenya Financial Inclusion Exploratory Data Analysis (EDA) 2024

An automated, modular end-to-end data pipeline analyzing household survey data from the **Kenya FinAccess 2024 Dataset**. This project investigates financial access, geographic distribution of respondents, and correlation structures between household wealth indicators and credit formalization across Kenya.

---

## 🚀 Project Architecture

The project follows professional software engineering and data science best practices, separating data ingestion, preprocessing, and analytical visualization into clean, maintainable modules:

```text
kenya-financial-inclusion-eda/
│
├── data/                       # Raw Stata dataset (ignored by Git)
├── outputs/                    # Generated analytical charts and visual assets
├── src/                        # Source code modules
│   ├── __init__.py
│   ├── data_loader.py          # Handles safe ingestion of Stata (.dta) files
│   ├── preprocessing.py        # Cleans, inspects, and encodes dataset features
│   └── eda_analysis.py         # Generates statistical distributions and heatmaps
│
├── .gitignore                  # Excludes large files, virtual envs, and cache
├── main.py                     # Master orchestration script
└── README.md                   # Project documentation