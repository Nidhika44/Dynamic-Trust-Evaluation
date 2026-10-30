# Dynamic Trust Evaluation

**Dr. Nidhika Chauhan**  
nidhi29.chauhan@gmail.com

## Setup

Use Python 3.12 or later:

```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m jupyterlab
```

Open `Implementation.ipynb` and run all cells in order. No external dataset is
required. Configuration and random seeds are defined in the first code cell.
The full experiment and parameter sweeps can take several hours.

Generated CSV tables, figures, compressed arrays, and experiment metadata are saved
to `evaluation_outputs/` in the working directory. This folder is ignored by Git.
