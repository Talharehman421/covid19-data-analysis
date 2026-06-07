# 🦠 COVID-19 Data Analysis: India & Global Insights

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0-green)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange)](https://matplotlib.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

A comprehensive end-to-end data analysis project exploring COVID-19 spread, vaccination rollout, and testing patterns across India and 226 countries worldwide.

---

## 📌 Project Overview

This project analyzes 4 real-world datasets from Kaggle to answer key public health questions:

- Which Indian states were most severely impacted?
- How did India's Wave 1 and Wave 2 compare in intensity?
- How did the vaccination rollout progress by state, brand, and gender?
- What does the test positivity rate reveal about hidden case burden?
- How does India compare to global peers like the USA, Brazil, and UK?

---

## 📊 Key Findings

| Finding | Detail |
|---------|--------|
| **Maharashtra #1** | ~25% of all India cases across both waves |
| **Wave 2 was 3× more intense** | Delta variant drove Apr–May 2021 spike |
| **CoviShield = 85% of doses** | Covaxin covered ~14% nationally |
| **Dose 2 gap** | Only ~35% of Dose 1 recipients had Dose 2 by July 2021 |
| **Positivity rate hit 20%+** | Actual cases likely 4–5× official counts |
| **India briefly overtook USA** | Daily cases in April 2021 |

---

## 📁 Project Structure

```
covid19-analysis/
│
├── data/
│   ├── raw/                         ← Original Kaggle datasets
│   └── cleaned/                     ← Processed, analysis-ready CSVs
│
├── notebooks/
│   └── COVID19_Analysis.ipynb       ← Main analysis notebook (11 visualizations)
│
├── outputs/
│   └── charts/                      ← All generated chart PNGs
│       ├── 01_top10_states.png
│       ├── 02_india_trend.png
│       ├── 03_fatality_heatmap.png
│       ├── 04_monthly_heatmap.png
│       ├── 05_vaccination_trend.png
│       ├── 06_state_vaccination.png
│       ├── 07_testing_analysis.png
│       ├── 08_state_positivity.png
│       ├── 09_global_top10.png
│       ├── 10_global_trend.png
│       └── 11_india_vs_world.png
│
├── README.md
└── requirements.txt
```

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading, cleaning, transformation |
| `numpy` | Numerical operations, derived metrics |
| `matplotlib` | Static charts, multi-panel figures |
| `seaborn` | Heatmaps, statistical visualizations |
| `folium` | Interactive geo maps |
| `jupyter` | Notebook environment |

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Talharehman421/covid19-analysis.git
cd covid19-analysis

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook notebooks/COVID19_Analysis.ipynb
```

---

## 📦 Requirements

```
pandas>=2.0
numpy>=1.24
matplotlib>=3.7
seaborn>=0.12
folium>=0.14
jupyter>=1.0
```

---

## 📂 Dataset Sources

- **COVID-19 India**: [Kaggle — sudalairajkumar/covid19-in-india](https://www.kaggle.com/datasets/sudalairajkumar/covid19-in-india)
- **Worldometer Global**: [Kaggle — josephassaker/covid19-global-dataset](https://www.kaggle.com/datasets/josephassaker/covid19-global-dataset)

---

## 👤 Author

**Talha Rehman**  
M.Sc. Bioinformatics — Pondicherry University  
📧 talharehmanhcs421@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/talha-rehman-532342212) · [GitHub](https://github.com/Talharehman421)

---

## 📄 License

This project is licensed under the MIT License.
