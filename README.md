# Market Structure Analysis using Independent Component Analysis (ICA)

## Overview 

This project applies **Independent Component Analysis (ICA)** and compares it with **Principal Component Analysis (PCA)** to identify underlying factors driving stock market returns, specifically focusing on the CAC 40 index.

## Project Goals

- Analyze market structure using ICA to extract economically interpretable independent factors.
- Reconstruct market indices using extracted independent components.
- Compare ICA results with traditional PCA in terms of interpretability and reconstruction accuracy.

## Data & Methodology

- Daily closing prices of CAC 40 index components (2001-2010).
- Computed daily log-returns as analysis input.
- Preprocessed data for stationarity and normality analysis.

## Key Results

- ICA effectively isolates key market shocks, highlighting significant financial events (e.g., 2008 financial crisis).
- PCA provides smoother reconstructions, capturing overall variance efficiently, but with less economic interpretability.
- Thresholding ICA components reveals trade-offs between reducing noise and losing significant market information.

## Tools & Technologies

- Python (NumPy, SciPy, Pandas, Matplotlib)
- Jupyter Notebook
