# Food Process Optimization via DoE & Response Surface Methodology (Python)

## 📌 Project Overview
An automated Design of Experiments (DoE) and Response Surface Methodology (RSM) pipeline built in Python to optimize plant-based protein extraction yield and functional quality parameters from agricultural side-streams.

## 🛠️ Tech Stack & Libraries
* **Experimental Matrix:** Custom Factorial & Box-Behnken Design workflows
* **Statistical Modeling & ANOVA:** `statsmodels` (OLS Regression)
* **Data Manipulation & Visualization:** `pandas`, `numpy`, `matplotlib`, `seaborn`

## 📊 Methodology & Key Steps
1. **Design Generation:** Structured 3-factor (Temperature, pH, Time) experimental matrix with center points to account for experimental variance.
2. **Response Simulation:** Modeled non-linear and interaction effects simulating protein extraction yield percentage.
3. **ANOVA & Validation:** Evaluated model significance ($R^2 > 0.95$) and individual factor $p$-values.
4. **Response Surface Mapping:** Generated 2D contour surfaces to isolate the optimal operating zone and reduce physical trial iterations.

## 🚀 How to Run
Open the `Food_Protein_Extraction_DoE.ipynb` notebook directly in Google Colab and run the cells sequentially.
