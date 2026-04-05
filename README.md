# 🏏 IPL T20 Cricket Strategy Analyzer

> Investigating the shift in T20 batting aggression and its impact on team scoring patterns across IPL seasons (2008–2025)

---

## 📌 Overview

Modern T20 cricket has seen a dramatic shift in batting philosophy — teams now attack from ball one, chasing 200+ in every match. But is this aggression always working?

This project investigates whether the post-2023 "fearless batting" trend is leading to **systematic score underperformance** — where teams lose crucial top-order wickets in the powerplay and fail to capitalize in the death overs.

---

## 🔬 Research Hypotheses

- **H1** — Powerplay run rates have increased significantly post-2023, but so have powerplay wickets lost
- **H2** — Teams losing 3+ wickets in the powerplay consistently underperform their projected score
- **H3** — Caught-out dismissals are rising year-on-year as batters attempt more aerial shots
- **H4** — The "projected score collapse" pattern (PP projection → middle over drop → final score) is measurable and consistent

---

## 📂 Dataset

| Property | Details |
|---|---|
| Source | Kaggle — IPL Ball-by-Ball Dataset |
| Records | 278,000+ deliveries |
| Seasons | 2008 – 2025 |
| Matches | 1,169 matches |
| Key columns | `over`, `runs_batter`, `wicket_kind`, `bat_pos`, `batting_team`, `year` |

---

## 🛠️ Tech Stack

- **Python** — Core language
- **Pandas & NumPy** — Data cleaning and manipulation
- **Scikit-learn** — ML algorithms (Regression, Clustering, Classification)
- **Matplotlib & Seaborn** — Visualizations
- **Jupyter Notebook** — Analysis environment

---

## 📊 Planned Analysis

```
Phase 1 — Data Cleaning & Feature Engineering
  └── Powerplay / Middle / Death phase tagging
  └── Projected score calculation per over
  └── Pre vs Post 2023 split

Phase 2 — Exploratory Analysis
  └── Year-wise PP run rate trend
  └── Dismissal type shift (caught vs bowled/lbw)
  └── Score collapse pattern visualization

Phase 3 — ML Models
  └── Regression → Predict final score from PP stats
  └── Clustering → Group innings archetypes
  └── Classification → Predict score underperformance from PP data
```

---

## 📁 Project Structure

```
ipl-batting-analyzer/
│
├── data/
│   └── IPL.csv                  # Raw ball-by-ball dataset
│
├── notebooks/
│   ├── 01_cleaning.ipynb        # Data cleaning & feature engineering
│   ├── 02_eda.ipynb             # Exploratory data analysis
│   └── 03_ml_models.ipynb       # ML model building & evaluation
│
├── outputs/
│   └── charts/                  # Saved visualizations
│
└── README.md
```

---

## 🚧 Status

**In Progress** — Analysis and model building ongoing

---

## 👤 Author

**Anas Quazi**
2nd Year B.Tech CSE | DY Patil International University, Pune
[GitHub](https://github.com/Anas-Quazi) | [LinkedIn](https://linkedin.com/in/muhammad-anas-quazi)