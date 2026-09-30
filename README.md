# DABN13 — Assignment 2: PCR and Regularization

Solved notebook, data included.

## Setup

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name=dabn13_a2 --display-name "Python (DABN13 A2)"
```

Windows: `.venv\Scripts\Activate.ps1` instead of `source .venv/bin/activate`.

Open `2.code/Assignment_2_template-1.ipynb`, select the `dabn13_a2` kernel.

## Layout

```
.
├── requirements.txt
├── 1.data/
│   ├── Airfares.csv.gz
│   ├── sorted_portfolios100.csv
│   └── twelve_month_returns.csv
└── 2.code/
    └── Assignment_2_template-1.ipynb
```

Notebook does `chdir('../1.data')` then reads by bare filename — keep it inside `2.code/`.

Rename before submission: `assignment_2_group_X.ipynb`.
