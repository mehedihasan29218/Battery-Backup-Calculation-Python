Tower DC Battery Backup Calculation – Python
Overview
This project automates the processing of multiple Excel files using Python, consolidates them into a single structured dataset, and calculates DC battery backup duration for telecom towers. The solution improves accuracy, scalability, and efficiency in power reliability analysis.

Business Use Case
•	Assess tower power resilience during outages
•	Monitor DC battery backup capacity
•	Reduce manual Excel consolidation effort
•	Support operational and maintenance planning

End-to-End Workflow
1.	Python script reads multiple Excel input files
2.	Data is cleaned, standardized, and merged
3.	A final consolidated Excel file is generated
4.	Battery backup duration is calculated based on load and capacity
5.	Output file supports reporting and further analytics

Tools & Technologies
•	Python (pandas, openpyxl)
•	Excel
•	File system automation

Key Calculations
•	DC battery capacity normalization
•	Load-based backup time calculation
•	Site-wise backup duration analysis

Repository Structure
battery-backup-calculation-python/
│
├── README.md
├── input_files/
│   └── sample_input_files.xlsx
│
├── scripts/
│   └── battery_backup_calculation.py
│
├── output/
│   └── final_battery_backup_report.xlsx
│
└── docs/
    └── calculation_logic.md

