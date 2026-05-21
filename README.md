# HBAAC Round 2 — Lemon team: Forecasting System Pipeline 

This repository contains the source code and production-ready pipeline developed by **LemonTeam** for Round 2 of the **HBAAC 2026** competition. 

Our solution focuses on solving a time series forecasting problem eliminating out-of-memory (OOM) bottlenecks using a **Vectorized Pivot Matrix Layout** and a **Multi-Tier Statistical Grouping Strategy**.

---

## 📂 Repository Structure

```text
HBAAC_round2_LemonTeam_pipeline/
├── main.py                                   # End-to-end forecasting pipeline (All-in-one execution)
└── README.md                                 # Documentation and project overview
```
How to Run

---

1. Clone the repository

```bash
git clone https://github.com/buiduan07/HBAAC_round2_LemonTeam_pipeline.git
cd HBAAC_round2_LemonTeam_pipeline
```
2. Prepare data & requirements
Ensure you have pandas and numpy installed. Place the competition's train.csv and sample_submission.csv inside your directory.

3. Run Execution
Execute the entire pipeline with a single command:

```bash
python main.py
```

The script will handle data cleaning, pivot indexing, dynamic SKU grouping, forecasting, and formatting sequentially. Your final submission file submission.csv will be generated in the root workspace in less than 90 seconds.

Developed by Lemon team for HBAAC 2026.
