# Merck 2026 Project

## Conda Environment Setup

This project uses a conda virtual environment named `merck_2026`.

### Activate the environment:
```bash
conda activate merck_2026
```

### Deactivate the environment:
```bash
conda deactivate
```

### Installed Packages:
- Python 3.11
- Jupyter & JupyterLab
- Pandas (data manipulation)
- NumPy (numerical computing)
- Altair (data visualization)

### To recreate the environment from scratch:
```bash
conda env create -f environment.yml
```

### To update the environment:
```bash
conda env update -f environment.yml --prune
```

### To launch Jupyter:
```bash
conda activate merck_2026
jupyter lab
```
