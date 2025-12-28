# Smoothness-constraints-for-instantaneous-state-InSAR
A simulation tool that allows adjustment of the velocity standard deviation and velocity decorrelation time, enabling the generation of noise-free simulated signals for selecting appropriate parameter settings for instantaneous state InSAR. 

## Repository Structure
- `smoothness_simulation.ipynb` — Main Jupyter Notebook
- `requirements.txt` — Python dependencies
- `environment.yml` — Conda environment
- `README.md`

## Environment Setup
- Python **3.10** or **3.11**
- Jupyter Notebook

### Option 1: Using `conda` (recommended)
```bash
conda env create -f environment.yml
conda activate insar-smoothness-env
```

### Option 2: Using `pip`
```bash
pip install -r requirements.txt
```

## How to Run the Notebook
After activating the environment:
```bash
jupyter notebook
```

### Steps to run:
1. In the Jupyter dashboard, locate the notebook file.
2. Open: `smoothness_simulation.ipynb`
3. Ensure the kernel is set to `insar-smoothness-env`.
