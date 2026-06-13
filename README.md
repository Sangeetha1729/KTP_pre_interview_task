# KTP Pre-Interview Task

Exploratory analysis and modelling of accelerated stability data for two prototype
pharmaceutical formulations (Lot A014 and Lot B025), prepared as part of a KTP
Associate pre-interview data analysis exercise.

The notebook addresses the following questions using the supplied dataset:

1. What are the key features of the dataset?
2. What insights can be gained from the available data?
3. What factors appear to influence product degradation?
4. How would you describe the relative performance of the two prototype formulations?
5. What additional insights can be obtained through modelling?
6. What are the limitations of the dataset and how could future studies be improved?

## Repository contents

- `KTP_Task.ipynb` — Jupyter notebook containing all code, plots, and commentary.

Note: the underlying dataset (`KTP_task_datasets.xls`) is **not** included in this
repository, in line with the submission instructions.

## Requirements

- Python 3.9+
- Jupyter Notebook or JupyterLab

Required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels xlrd
```

## How to run

1. Clone this repository.
2. Place a copy of `KTP_task_datasets.xls` in the same directory as `KTP_Task.ipynb`
   (the notebook expects the two sheets `Lot A014` and `Lot B025` in this file).
3. Launch Jupyter and open the notebook:

```bash
jupyter notebook KTP_Task.ipynb
```

4. Run all cells from top to bottom (Kernel → Restart & Run All).
