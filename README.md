# Linear Regression Explainability — Diabetes Dataset

Module 2 exercise: explaining a linear regression model using `statsmodels`
on scikit-learn's diabetes dataset, in a Jupyter notebook with cell-by-cell
explanations and outputs.

## Setup

```bash
python3 -m venv venv
source venv/bin/activate      # on Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Run

Open in VS Code (with the Jupyter extension) or Jupyter Lab:

```bash
jupyter lab linear_regression_explainability.ipynb
```

Run each cell top to bottom with Shift+Enter to see the output build up
step by step: data loading, correlation heatmap, model fit, performance
metrics, and the feature importance plot.

## Key finding
`bmi` and `s5` are the strongest statistically significant positive
predictors of diabetes progression in this dataset; `sex` has a smaller
but significant negative effect. R² = 0.51, meaning the model explains
about half the variance in the outcome.
