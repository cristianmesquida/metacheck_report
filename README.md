# Description

This repository accompanies the report "Supporting Master’s Students and Supervisors with Metacheck - Project Report"
All analyses, including data processing and descriptive analyses are documented in `report.qmd`.

To render only the manuscript, run:

```bash
quarto render report.qmd
```

# Repository structure

```text
metacheck_report/
├── pdf_theses/              # Master’s theses in PDF format
│
├── json_theses/             # Master’s theses converted to JSON format
│
├── results/                 # Directory for storing results
│   ├── json_theses.RDS      # RDS file containing the converted theses
│   ├── res_repo_check.RDS   # RDS file containing information extracted by the `repo_check` module
│   ├── res_llm_power.RDS    # RDS file containing information extracted by the `power` module using LLM support
│   └── survey_results.xlsx  # XLSX file containing the answers from the respondents
│    
├── report.qmd               # Quarto source file
├── report.html              # Rendered project report
└── session-info.txt         # R session information
```