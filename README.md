# COMP2200 Data 001

Payroll, revenue, and media-coverage forecasts for one company, 12 months ahead. The analysis is in `assignment1.ipynb`.

This project does not use an API key, password, token, or `.env` file. `company_data.csv` is the company dataset supplied with the assignment.

## Run

Use Python 3.10 or newer.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Keep `company_data.csv` in the same folder as `assignment1.ipynb`, then start Jupyter from that folder:

```bash
jupyter notebook assignment1.ipynb
```

Use **Kernel → Restart & Run All**. The notebook reads `company_data.csv` and refits the models from the top.
