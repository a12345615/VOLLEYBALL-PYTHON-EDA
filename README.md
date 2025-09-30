# VOLLEYBALL-PYTHON-EDA
🏐 Exploratory Data Analysis of Volleyball Nations League players. Includes stats, rankings, correlations, and visualizations (boxplots, scatter, heatmap) with clean outputs in Excel, CSV, and plots.
# 🏐 Volleyball Players EDA

Exploratory Data Analysis (EDA) of **Volleyball Nations League players** dataset.  
It analyzes performance metrics such as **Attack, Block, Serve, Set, Dig, and Receive**, and provides insights at both **player-level** and **country-level**.

---
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

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
<img width="1473" height="715" alt="Screenshot 2025-09-30 142608 - Copy" src="https://github.com/user-attachments/assets/37378106-6e6d-42b9-912e-3c52e0c6bca7" />

<img width="1486" height="762" alt="Screenshot 2025-09-30 142848 - Copy" src="https://github.com/user-attachments/assets/163474f5-0a3a-472a-889c-5c7c58c056f0" />
<img width="1047" height="625" alt="Screenshot 2025-09-30 142938 - Copy" src="https://github.com/user-attachments/assets/cf054884-ef1a-4269-bf7e-ecf80653a1f5" />


## 🚀 Features
- Clean dataset (no missing values).  
- Descriptive statistics & player performance summaries.  
- **Top-10 players** by each metric.  
- Country & position-level insights.  
- Correlation analysis & role differences.  
- Visualizations: boxplots, scatter plots, heatmap.
- <img width="1485" height="794" alt="Screenshot 2025-09-30 142958 - Copy" src="https://github.com/user-attachments/assets/6a6f5216-442e-4e00-89f4-eb2d2a097f51" />
 <img width="1482" height="613" alt="Screenshot 2025-09-30 143022 - Copy" src="https://github.com/user-attachments/assets/19b7397d-a4f3-4857-a183-4c1a638d07ae" />

<img width="785" height="573" alt="Screenshot 2025-09-30 143038 - Copy" src="https://github.com/user-attachments/assets/e7b84f11-dd09-4e67-9231-880c3b3ff64b" />
<img width="1015" height="704" alt="Screenshot 2025-09-30 143057 - Copy" src="https://github.com/user-attachments/assets/bf0be93e-958d-4f17-b963-9da4477735da" />

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
- <img width="1483" height="755" alt="Screenshot 2025-09-30 143132 - Copy" src="https://github.com/user-attachments/assets/114597ca-8023-440f-aeb0-b8fe3774d25e" />

<img width="1170" height="733" alt="Screenshot 2025-09-30 143113" src="https://github.com/user-attachments/assets/2e127f85-b7aa-4d22-81b9-94f78e7d737a" />

---

## 📦 Requirements
- Python 3.8+  
- pandas  
- matplotlib  
- seaborn  
- openpyxl
- <img width="1481" height="758" alt="Screenshot 2025-09-30 143155 - Copy" src="https://github.com/user-attachments/assets/54626c70-35b7-4ffd-afaa-f6455461b2b9" />
<img width="1486" height="790" alt="Screenshot 2025-09-30 143214 - Copy" src="https://github.com/user-attachments/assets/2f4b88c7-4ea5-45c8-85b3-2d35816a72a4" />


Install with:
```bash
pip install -r requirements.txt
```

---

👨‍💻 Author: *EDA Analyst (Volleyball Data Project)*

