# IS 362 — Week 8: Auto MPG EDA

## Contents
- `IS362_Week8_AutoMPG.ipynb` — reproducible notebook: load → clean → transform → visualize.
- `auto_mpg_clean.csv` — cleaned dataset (horsepower fixed and origin mapped).
- `cylinders_bar.png` — cylinders distribution (bar).
- `hp_weight_scatter.png` — horsepower vs weight (scatter).
- `mpg_by_cylinders_box.png` — MPG by cylinders (boxplot).

## Data Source
UCI Machine Learning Repository — Auto MPG (auto-mpg.data, auto-mpg.names).

## Reproducibility
Environment: Python 3.11+, packages: pandas, numpy, matplotlib.

Steps:
1. Open the notebook and run all cells.
2. Outputs are saved to the same folder as PNG files and a cleaned CSV.

## Notes
- `horsepower` missing values marked as `?` are converted to NaN before numeric casting.
- `origin` codes `1/2/3` are mapped to `USA/Asia/Europe`.
