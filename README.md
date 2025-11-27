# Étude de Cas 2 — BCG  
Analysis of Climate-Driven Risks on Barley Production in France

This repository contains the full analytical workflow used to evaluate climate impacts on barley yields across French regions, compute a global BCPI indicator (Barley Climate Performance Index), and produce strategic insights aligned with a consulting deliverable.

---

## Getting Started

### Data 
All scripts and notebooks expect the input data to be placed in a data/ folder at the root of the project:
```text
project/
│
├─ data/
│   ├─ barley_yield_from_1982.csv (to add)
│   └─ climate_data_from_1982.parquet (to add)
│
├─ intermediate_point.ipynb
├─ main.ipynb
└─ README.md
```

### Environment setup

You can either use **uv** (recommended) or a standard Python environment.

In either case you just launch a jupyter server. When using UV
```bash
uv run --with jupyter jupyter notebook
```

If you are using python, you should create a virtual env

```bash
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```