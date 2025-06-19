# Mini-Project-Analysis-of-Global-CO-Emissions
Project Goal:  Analyze global CO₂ emissions trends over time, identify the top emitters, and visualize key insights using pandas, matplotlib, and seaborn.

#Global CO₂ Emissions Analysis

This mini project analyzes global CO₂ emissions using `pandas`, `matplotlib`, and `seaborn`.  
It was built and executed in **Google Colab** for easy access and reproducibility.

---

## Dataset

Data source: [Our World in Data - CO₂ Dataset](https://github.com/owid/co2-data)  
We use the `owid-co2-data.csv` file, downloaded directly from the GitHub repository.

---

## How to Run (in Google Colab)

1. Open the notebook in Google Colab  
2. Run the first cell to download the dataset:
   ```python
   !mkdir -p data
   !wget -O data/owid-co2-data.csv https://github.com/owid/co2-data/raw/master/owid-co2-data.csv

