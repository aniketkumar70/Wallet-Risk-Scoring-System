# 🛡️ Wallet Risk Scoring System

This repository contains the solution, which involves building a wallet risk scoring system from scratch using on-chain activity data.

---

## 📂 Submission Contents

| File Name                                     | Description |
|----------------------------------------------|-------------|
| `wallet_risk_scores.csv`                     | Final output file containing wallet addresses and their risk scores (0–1000 scale). |
| `Round_2_Assignment_Wallet_Risk_Scoring_From_Scratch.ipynb` | Jupyter Notebook with the complete pipeline: data loading, filtering, feature extraction, scoring, and CSV generation. |
| `wallet_risk_documentation.pdf`              | Comprehensive technical report explaining the methodology, feature design, and risk logic. |
| `wallet_risk_dashboard.png`                  | Visualization dashboard showing score distribution, risk categories, and insights. |

---

## 🎯 Problem Statement

Given a list of 103 wallet addresses, the objective was to:
1. Fetch their transaction history from the Compound V2/V3 protocol.
2. Engineer meaningful features that reflect risk exposure.
3. Assign a risk score between 0 and 1000 for each wallet.
4. Justify the scoring logic using DeFi and financial risk modeling principles.

---

## 📊 Key Highlights

- ✅ **No transaction history found** for the provided wallets on Compound V2/V3.
- ⚙️ Implemented **deterministic feature simulation** using wallet hashes (e.g., account age, asset diversity).
- 🧠 Designed a **weighted multi-factor scoring model** based on:
  - Activity (25%)
  - Volume (20%)
  - Behavioral Patterns (25%)
  - Diversification (15%)
  - Frequency (15%)
- 🧪 Used min-max normalization with edge case handling.
- 📉 Risk scores range: **319 to 544**, representing realistic differentiation for inactive wallets.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook
- Google Colab (Runtime)
- Excel + CSV for wallet ID alignment
- Markdown / PDF for documentation

---
