# ALT — 1‑Minute Futures Strategy (Assignment)

👋 **Welcome!** This repository contains my solution to an interview task: design and evaluate a **data‑driven trading strategy** on **1‑minute futures data**, optionally enhanced with **machine learning**.

---

## 📌 Task & Deliverables

**Task description**  
> According to the interview prompt: *write a trading strategy using 1‑minute futures data, possibly with machine learning.*

**Deliverables**  
1. **`1. exploration+preprocessing_v11.ipynb`** – Data exploration, sanity checks, and preprocessing.
2. **`2. strategy_backtest_v11.ipynb`** – Strategy logic design and historical backtest.
3. **`3. ML_backtest_v10.ipynb`** – Application of machine learning to the problem.
4. **`literature/`** – A few papers related to the proposed strategy (see below).

---

## 🗂️ Repository Structure

```
.
├── 1. exploration+preprocessing_v11.ipynb   # EDA, sanity checks, preprocessing
├── 2. strategy_backtest_v11.ipynb           # Feature-driven strategy & backtest
├── 3. ML_backtest_v10.ipynb                 # ML models & backtests
└── literature/                              # References and related reading
    ├── ...
    └── README (optional notes)
```

## 🧠 Method in a Nutshell

A **novel feature** is introduced based on the **Intrinsic Mode Function (IMF)** decomposition (see the attached literature for background).  
- The IMF‑based signal is used in both **algorithmic** (rules‑based) and **machine‑learning** setups.  
- Across the experiments, **both approaches show profitable results** under the tested assumptions.  
- **Conclusion:** IMF features demonstrate **strong potential** for commercial‑grade trading strategies, meriting further research (robustness checks, execution/frictions, and multi‑asset validation).

---

## ⚠️ Disclaimer

This repository is for **research/interview** purposes only and **not** financial advice. Past performance in backtests does not guarantee future results. Use at your own risk.

---

## 🧾 License & Contributions

opyright (c) 2025 Sla11. All rights reserved.

This repository and its contents are proprietary and confidential.
Unauthorized copying, modification, distribution, or use of this software,
via any medium, is strictly prohibited without express written permission
from the copyright holder.
