# AI-Product-Orchestrator-Meta-AI-
A clear project overview: what it does, why it matters, and real-world use-cases.  A complete, runnable Python script that: generates a sample dataset, cleans it, engineers features, performs EDA, trains a Random Forest regression model (with optional LSTM snippet), evaluates using RMSE and R², and visualizes actual vs predicted values. 

# 치AI Product Orchestrator (Meta-AI)

**Industry-oriented data science project**: end-to-end demand forecasting and orchestration prototype.

---

## Project summary
치AI Product Orchestrator predicts product demand at monthly granularity and produces orchestration-ready outputs to help product, supply chain, and marketing teams make automated decisions. This repository demonstrates data ingestion, cleaning, feature engineering, modeling (RandomForest), evaluation, and visualization.

---

## Features
- Synthetic dataset generator for quick experimentation
- Robust feature engineering: lag features, rolling means, seasonality encoding
- RandomForest regression baseline with RMSE & R² evaluation
- Visualizations: global & per-product actual vs predicted plots
- Artifacts saved for reuse (model/scaler)

---

## Quickstart

1. Clone repo:
```bash
git clone git@github.com:yourusername/chiAI-Product-Orchestrator.git
cd chiAI-Product-Orchestrator
