# Autoencoder Exploration - FashionMNIST

This repository contains the following artifacts for the Autoencoder exploration assignment:

- `Autoencoder_Exploration.ipynb` — Full Jupyter notebook with code, experiments, visualizations, and commentary (PyTorch).
- `Report.pdf` — Short reflective report (<=10 pages) summarizing methodology, results and reflections.
- `README.md` — This file.

## Requirements
- Python 3.8+
- torch, torchvision, matplotlib, numpy, jupyter
- For GPU training: CUDA-enabled PyTorch build.

Install dependencies (example):
```bash
pip install torch torchvision matplotlib numpy jupyter notebook
```

## How to run
1. Open the notebook:
```bash
jupyter notebook Autoencoder_Exploration.ipynb
```
2. Run the notebook cells sequentially. The notebook downloads Fashion-MNIST automatically.
3. Outputs (checkpoints, images) will be saved to `outputs_autoencoder/` in the working directory.

## Notes
- The notebook is designed for clarity and reproducibility. It contains a Conv AE baseline, VAE, Beta-VAE experiments, latent interpolation, and a latent-dim sweep.
- If you want to run faster reduce `n_epochs` or `batch_size` in the top cells.
- If you use the notebook in a remote environment, ensure `num_workers` in DataLoader is appropriate for the environment.
