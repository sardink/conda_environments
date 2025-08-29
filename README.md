# Environments Repository

This repository is used to save and maintain environment specification files (`.yml`) for reproducible development.  
Each file defines a conda/mamba environment tailored to specific use cases in academic work, financial engineering, and data science.

---

## Included Environments

### `data_science_env` *(deprecated)*
- **Purpose:** General Python training for coursework and assignments.  
- **Status:** No longer maintained. Superseded by `fe_base`.

### `fe_base`
- **Purpose:** Baseline template for **financial engineering** and **data science** studies.  
- **Includes:**
  - Core numerical libraries (`numpy`, `scipy`, `pandas`)  
  - Statistical/econometric libraries (`statsmodels`, `arch`)  
  - Visualization (`matplotlib`, `seaborn`)  
  - Data access (`yfinance`)   
