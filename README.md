# Garza — 12-month outlook

Payroll, revenue, and media coverage for month 36, fit on the 24 months in `company_data.csv`.

| File | What it is |
| --- | --- |
| `assignment1.ipynb` | The analysis, with the figures printed under each model |
| `company_data.csv` | Monthly payroll, revenue, scandals, and media coverage |
| `one-year-outlook.mp4` | Two-minute walkthrough of the month-36 results |

The video quotes these figures from the notebook:

- Payroll in month 36 is about $3.76 million. The band under that cell is about $3.66 million to $3.86 million.
- Revenue in month 36 is about $3.66 million, after the log forecast is turned back into dollars.
- Negative media coverage is the likely continuation. The printed probability of 1.00 is not a calibrated certainty.

## Run

Python 3.10 or newer. From this folder:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook assignment1.ipynb
```

Leave `company_data.csv` next to the notebook, then use Kernel, Restart and Run All.
