# Copula Modeling Short Course

A comprehensive course on copula modeling for dependence analysis, covering theory and practical applications in Python.

## Course Structure

### Notebooks (`notebooks/`)

| # | Topic | Description |
|---|-------|-------------|
| 1 | Introduction | Course overview and motivation |
| 2 | Pearson Correlation | Classical correlation coefficient |
| 3 | Correlation Deficiencies | Limitations of linear correlation |
| 4 | Dependence Metrics | Kendall's tau, Spearman's rho |
| 5 | Beyond Metrics | Why metrics aren't enough |
| 6 | Copula Introduction | Sklar's theorem, copula fundamentals |
| 7 | Closed-Form Copulas | Gaussian, Student-t, Clayton, Gumbel, Frank |
| 8 | Fitting Data | Parameter estimation, model selection |
| 9 | Vine Copulas Intro | High-dimensional dependence |
| 10 | Vine Copula Inference | Fitting and simulation |
| 11 | AMH Estimation | Ali-Mikhail-Haq copula |
| 13 | Univariate Time Series | GARCH, copula residuals |
| 14 | Multivariate Time Series | DCC-GARCH, vine copulas |

### Supplemental Materials (`course-materials/`)

- **Case Studies**: Crypto risk modeling, energy market spark spreads
- **Reference Guides**: Cheat sheet, copula selection flowchart, Python library comparison
- **Practice**: Exercises with solutions, code templates
- **Certificate**: Completion certificate template

### Data (`data/`)

- PJM electricity prices (2022-2024)
- Henry Hub natural gas futures

## Setup

```bash
# Create environment and install dependencies
uv sync

# Run Jupyter
uv run jupyter notebook
```

## YouTube

Video lectures available at: https://www.youtube.com/@kirankarra87

## License

All rights reserved.
