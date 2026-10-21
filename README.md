This repository provides the core codebase accompanying the project titled "Addressing the Rashomon Effect in Machine Learning-Based Discovery of Water Splitting Dual-Atom Catalysts Through Cross-Model Consensus".

## Jupyter Notebook
All code was developed using Python v3.12.2 and executed in this [`Jupyter Notebook`](./notebook_v1.0.0.ipynb). The relevant software packages required to run this code are listed in the [`requirements`](./requirements.txt).

## Data
The DFT dataset used in this research comprises transition-metal dual-atom catalysts on a two-dimensional nitrogen-doped carbon support. It is not publicly available due to confidentiality. However, the [`Jupyter Notebook`](./notebook_v1.0.0.ipynb) expects the following data files in base_dir:

| File | DFT Total Energy (eV) |
|---|---|
| `data/all_data/final_energies_H.csv` | DAC slab with adsorbed H intermediate |
| `data/all_data/final_energies_O.csv` | DAC slab with adsorbed O intermediate |
| `data/all_data/final_energies_OH.csv` | DAC slab with adsorbed OH intermediate |
| `data/all_data/final_energies_OOH.csv` | DAC slab with adsorbed OOH intermediate |
| `data/slab_data/final_energies_slab.csv` | DAC slab with no adsorbed intermediates |

In each file, one row represents one dual-atom catalyst pair, and there are three columns corresponding to the first metal, the second metal, and the DFT total energy.
