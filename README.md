# CAS-AML: Predicting Returns or Risk? ML Evidence from the Nasdaq-100 ETF

Final project, CAS Advanced Machine Learning, University of Bern (2026).
Author: Wjera Yell Leutenegger — wjera.leutenegger@unibe.ch

Which aspects of QQQ are predictable with ML? Using a 2007–2026 daily panel, the project
predicts return direction, return level, realized volatility and stress, evaluated under a
purged walk-forward protocol. Finding: little return predictability, but volatility and
stress are predictable — though the VIX captures most of it and no strategy survives costs.

`Final_WYLeutenegger.ipynb` holds the full analysis. Data: Refinitiv, Yahoo, FRED.
Run the notebook top to bottom (Python 3.11+: numpy, pandas, scikit-learn, xgboost, optuna, arch, scipy).
