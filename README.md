# News Shareability Prediction
### Regression Task

## Overview
This project builds a **regression pipeline to predict the shareability of online news articles** based on their features. The work follows an extensive analysis of preprocessing techniques and model selection, comparing multiple approaches to minimise prediction error.

Report title: *"If it doesn't spread, it's dead"*

## Approach

### Exploratory Data Analysis
- Automated EDA report generated with SweetViz (`sweet_report.html`)
- Distribution analysis, correlation matrix, feature importance exploration
- Identification of relevant predictors of shareability

### Preprocessing
- Feature selection and engineering
- Handling of skewed distributions
- Scaling and transformation strategies

### Models Tested
A wide variety of regression models evaluated and compared:
- Linear Regression, Lasso, Ridge
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting variants

### Pipeline
Built with **Scikit-learn** pipelines integrating preprocessing and model steps for clean, reproducible experimentation.

## Repository Structure
```
RegressionTaskNewsSharebility/
├── Report.ipynb              ← full analysis and modelling notebook
├── sweet_report.html         ← automated EDA report (open in browser)
├── Submission.csv            ← final predictions
├── requirements.txt          ← Python dependencies
└── Report_If it doesn't spread_ it's dead.pdf  ← full project report
```

## How to Run

```bash
# Clone the repo
git clone https://github.com/siinvictus/RegressionTaskNewsSharebility.git
cd RegressionTaskNewsSharebility

# Install dependencies
pip install -r requirements.txt

# Open EDA report
open sweet_report.html   # or just drag into browser

# Run notebook
jupyter notebook Report.ipynb
```

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SweetViz, Jupyter

## Authors
Silva Bashllari & collaborators — Politecnico di Torino Course

## License
[Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)
