# HBAAC Round 2 — Lemon team: Forecasting System Pipeline 

This repository contains the source code and production-ready pipeline developed by **Lemon team** for Round 2 of the **HBAAC 2026** competition. 

Our solution focuses on solving a time series forecasting problem eliminating out-of-memory (OOM) bottlenecks using a **Vectorized Pivot Matrix Layout** and a **Multi-Tier Statistical Grouping Strategy**.

---

## Repository Structure

```text
HBAAC_round2_LemonTeam_pipeline/
├── main.py                                   # End-to-end forecasting pipeline (All-in-one execution)
└── README.md                                 # Documentation and project overview
```
---
## How to Run

### 🏢 Option 1: Running on Kaggle Notebook
If you are reproducing the results directly inside a Kaggle Notebook environment:
1. Upload `main.py` to your Kaggle session (or copy-paste the code into a notebook cell).
2. Ensure the competition datasets (`train.csv` and `sample_submission.csv`) are added to your notebook's input data.
3. The script will automatically scan `/kaggle/input/` recursively, detect the files, and execute.

### 💻 Option 2: Running on Local Machine
If you prefer to run the code locally on your workstation:
1. Clone this repository and navigate into it.
   ```bash
      git clone https://github.com/buiduan07/HBAAC_round2_LemonTeam_pipeline.git
      cd HBAAC_round2_LemonTeam_pipeline
    ```
3. Download `train.csv` and `sample_submission.csv` from the competition page.
4. Place both `.csv` data files directly into the root folder (the same directory containing `main.py`).
5. Run Execution
   ```bash
   python main.py
   ```
Developed by Lemon team for HBAAC 2026.
