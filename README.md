# Insulin Stabilization with RFdiffusion

This project explores the design of protease-resistant insulin using RFdiffusion.  
We identify cleavage-prone residues using Pepsickle, and then use RFdiffusion to design protective carriers.

## Project Structure

- `RFdiffusion/` – core model code (submodule or copied in)
- `notebooks/` – analysis & experiments
- `scripts/` – preprocessing, cleaning, and design automation
- `rf_output/` – design outputs (gitignored)
- `env/` – Conda environment files (optional)

## Requirements
- Python 3.9
- RFdiffusion (see `env/SE3nv.yml`)
- CUDA 12.1+

## Credits
Based on [RFdiffusion](https://github.com/RosettaCommons/RFdiffusion)
