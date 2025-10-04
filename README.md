# Performance Analysis of a Concentric Tube Heat Exchanger

This project analyzes experimental data from a **concentric (double-pipe) heat exchanger** using Python.  
It computes performance parameters, validates experimental results, and visualizes system behavior.  

---

##  Features
- Calculates **Log Mean Temperature Difference (LMTD)**
- Computes **Heat Duty (Q)** for hot & cold streams
- Estimates **Overall Heat Transfer Coefficient (UA)**
- Determines **Number of Transfer Units (NTU)** and **Effectiveness**
- Checks **energy balance error**
- Generates plots:
  - Effectiveness vs NTU
  - UA vs Mass Flow Rates
  - Energy Balance Error per Run

---

## Sample Results
| Run ID | Mode      | LMTD (K) | UA (W/m²-K) | NTU  | Effectiveness |
|--------|----------|-----------|-------------|------|---------------|
| 1      | Parallel | 19.97     | 29895       | 3.57 | 0.50          |
| 2      | Parallel | 18.49     | 30735       | 2.93 | 0.50          |
| 3      | Counter  | 17.96     | 34819       | 4.16 | 0.81          |
| 4      | Counter  | 19.86     | 49196       | 4.70 | 0.82          |

---

## ▶️ Run the Notebook
Open this project directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/utkarsh032211/heat-exchanger-performance-analysis/blob/main/heat_exchanger_analysis.ipynb)

---

##  Files in this Repository
- `heat_exchanger_analysis.ipynb` → Jupyter Notebook with full code & plots  
- `README.md` → Project documentation  
- *(Optional)* CSV of processed results & plots (you can upload)  

---

##  Applications
- Heat exchanger performance evaluation  
- Showcasing **mechanical + coding + data analysis skills** for placements  
- Basis for optimization & predictive modeling extensions  

---

👨‍💻 **Author:** Utkarsh Yadav  
📌 Final-year Mechanical Engineering Project
