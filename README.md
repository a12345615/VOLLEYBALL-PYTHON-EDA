# VOLLEYBALL-PYTHON-EDA
🏐 Exploratory Data Analysis of Volleyball Nations League players. Includes stats, rankings, correlations, and visualizations (boxplots, scatter, heatmap) with clean outputs in Excel, CSV, and plots.
# 🏐 Volleyball Players EDA

Exploratory Data Analysis (EDA) of **Volleyball Nations League players** dataset.  
It analyzes performance metrics such as **Attack, Block, Serve, Set, Dig, and Receive**, and provides insights at both **player-level** and **country-level**.

---
<img width="1473" height="715" alt="Screenshot 2025-09-30 142608" src="https://github.com/user-attachments/assets/2e7c3b61-ae82-4228-b20c-fa1b8068ab1c" />

## 📌 Description
This project focuses on analyzing player performance from the Volleyball Nations League.  
The dataset contains 131 players across 10 features, including demographics and performance metrics.  
Insights include **Top-10 rankings, role-based comparisons, country-level averages, and correlations**.  
Visualizations such as boxplots, scatter plots, and heatmaps make results clear and interpretable.  
Outputs are provided in **Excel, CSV, and plots** for easy reference.  

---

## 📂 Project Structure
```
volleyball-eda/
│── data/                     # Raw dataset (CSV)
│── src/                      # Python scripts
│   └── volleyball_eda.py     # Main EDA script
│── notebooks/                # Optional Jupyter notebooks
│── outputs/                  # Results (plots, reports, summaries)
│   ├── plots/                # Boxplots, scatter plots, heatmap
│   ├── volleyball_eda_report.xlsx
│   ├── volleyball_eda_summary.csv
│   └── summary.txt
│── README.md
│── requirements.txt
```

---
<img width="1028" height="670" alt="Screenshot 2025-09-30 142725 - Copy" src="https://github.com/user-attachments/assets/078464f6-fc2a-4726-a32f-7894397af294" />


## 🚀 Features
- Clean dataset (no missing values).  
- Descriptive statistics & player performance summaries.  
- **Top-10 players** by each metric.  
- Country & position-level insights.  
- Correlation analysis & role differences.  
- Visualizations: boxplots, scatter plots, heatmap.  

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/volleyball-eda.git
   cd volleyball-eda
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the EDA script:
   ```bash
   python src/volleyball_eda.py
   ```

4. Check results in the **outputs/** folder.

---

## 📑 Outputs
- **Excel Report** → Descriptive stats + Top-10 players by metric  
- **CSV Summary** → Numeric statistics  
- **Plots** → Boxplots, scatter plots, correlation heatmap  
- **Text Report** → Quick summary of dataset  

---

## 📦 Requirements
- Python 3.8+  
- pandas  
- matplotlib  
- seaborn  
- openpyxl  

Install with:
```bash
pip install -r requirements.txt
```

---

👨‍💻 Author: *EDA Analyst (Volleyball Data Project)*

