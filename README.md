# Thesis Analytics – FX Market Data Preparation

This repository contains the cleaned and ready-to-share version of the data preparation notebook used in the Master's thesis:

**Title:** *Dynamics of FX Trading: Analysing Correlations, Execution Efficiency, and Regulatory Impacts Across Past, Present, and Future Trends*  
**Author:** Alex Proschkin  
**Year:** 2025  
**Institution:** Frankfurt School of Finance & Management

## Repository Structure

```
/notebooks/
    └── Data_Prep_GithubReady.ipynb
    └── Data_Prep.ipynb #the one i used with output cells

/data/
    └── Output Data Tables
README.md
```

## Getting Started

1. Clone this repository:
```bash
git clone https://github.com/APFFM/2025-Master-Thesis.git
cd fx-thesis-analytics
```

2. Open the `notebooks/Data_Prep_GithubReady.ipynb` notebook.

3. Replace the data loading section with the confidential dataset path (see the commented cell in the notebook).

## Confidential Data Instructions

The full dataset used in the thesis is **not public** due to institutional confidentiality agreements.  
However, the notebook includes a clearly marked section for the supervisor to:

- Enter a **local file path** (e.g., `./data/thesis_dataset.csv`)
- Or mount a **Google Drive/Dropbox/FS Share link** that is password-protected

## Output

The notebook performs:
- Raw trade data cleaning
- Notional adjustment
- Execution cost calculations
- Export of clean `.csv` or `.xlsx` files for use in regression and analysis

For any questions, please contact:  
**📧 alex.proschkin@frankfurt-school.de** (or your academic advisor contact route)

---

*This repository serves academic purposes only.*
