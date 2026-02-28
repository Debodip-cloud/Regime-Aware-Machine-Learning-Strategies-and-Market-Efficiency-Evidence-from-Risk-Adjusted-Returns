![License](https://img.shields.io/badge/license-Proprietary-blue)
📊 Regime-Aware Portfolio Modeling and Performance Analysis

This repository contains the Jupyter notebook and supporting materials for a regime-aware financial modeling project. The project investigates how different market regimes affect portfolio performance and evaluates risk-adjusted returns using XGBoost-based allocation strategies.

🔍 Project Overview

The main goal of this project is to:

Analyze portfolio performance across Normal, Stress, and Crisis market regimes

Study the sensitivity of returns to volatility targets and regime scaling parameters

Compare performance metrics such as Sharpe ratio, Sortino ratio, and downside deviation

Generate publication-ready LaTeX tables for inclusion in academic manuscripts

The notebook implements a regime-aware simulation where portfolio allocation adapts depending on market volatility conditions, using both classical and machine learning-based techniques.

⚙️ Parameter Space

The study explores multiple combinations of:

Target Volatility (Target Vol): 0.05, 0.10, 0.15

Regime Scaling (Normal, Stress, Crisis): 0.6, 0.8, 1.0

Other model parameters: Risk-adjustment and allocation thresholds

For each combination, the following metrics are computed:

Portfolio return statistics under each regime

XGBoost-based risk-adjusted Sharpe and Sortino ratios

Downside and upside deviations

Sensitivity to regime scaling


🚀 How to Run the Notebook

Clone the repository:

git clone https://github.com/yourusername/your-repo-name.git

Navigate to the directory:

cd your-repo-name

Install dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Open and run the main notebook to reproduce all results.

🧪 Reproducibility

The simulations are deterministic given the parameter settings.

All tables and figures can be regenerated directly from the notebook.

No manual editing is required; outputs are automatically formatted for academic publication.

📦 Dependencies

Python 3.9+

NumPy

Pandas

Matplotlib / Seaborn

XGBoost

Jupyter Notebook

👤 Author
Debodip Chowdhury
📧 cdebodip@gmail.com

Debodip Chowdhury
📧 cdebodip@gmail.com
