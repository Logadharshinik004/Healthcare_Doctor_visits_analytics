HEALTHCARE ANALYTICS FOR DOCTOR VISITS — PROJECT FILES

Files:
1. Healthcare_Doctor_Visits_Analytics.ipynb
   Complete step-by-step notebook with cleaning, EDA, charts, correlation,
   an optional statistical test, and Power BI export instructions.

2. healthcare_doctor_visits_analysis.py
   Python script version of the core analysis.

3. healthcare_doctor_visits_powerbi.csv
   Cleaned analytical dataset for Power BI (row index removed; includes
   visit_status and exploratory numeric bands).

HOW TO RUN:
- Install Python and Jupyter Notebook, or use Google Colab.
- Put the original CSV in the notebook's working folder.
- Install packages if needed: pip install pandas numpy matplotlib seaborn scipy
- Open the notebook and run cells from top to bottom.
- For Power BI, import healthcare_doctor_visits_powerbi.csv.

IMPORTANT LIMITATIONS:
- age and income are numeric scales; confirm their units in the original
  data dictionary before assigning real-world labels.
- Confirm definitions for private, freepoor, freerepat, nchronic, lchronic.
- Findings are descriptive associations and do not prove causation.
