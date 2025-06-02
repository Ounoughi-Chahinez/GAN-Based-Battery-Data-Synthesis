# README: GAN-Based Battery Data Synthesis Notebooks

This repository contains four Jupyter notebooks demonstrating different types of Generative Adversarial Networks (GANs) for generating synthetic battery temperature data. These notebooks are designed for educational and experimental purposes within battery AI research and workshops.

## Notebooks Overview

### 1. **Vanilla GAN**
- **File:** `vanilla_gan.ipynb`
- **Description:** Generates synthetic battery temperature sequences without conditioning on external variables.
- **Use Case:** Baseline GAN learning for understanding adversarial training.

### 2. **Conditional GAN (cGAN)**
- **File:** `cgan.ipynb`
- **Description:** Generates temperature time-series conditioned on input variables such as:
  - State of Charge (SoC)
  - Cycle number
  - Ambient temperature
- **Use Case:** Controlled generation of context-specific battery profiles.

### 3. **Wasserstein GAN with Gradient Penalty (WGAN-GP)**
- **File:** `wgan_gp.ipynb`
- **Description:** Uses Wasserstein loss and gradient penalty to ensure stable GAN training.
- **Use Case:** High-quality, physically plausible data generation where model stability is essential.

### 4. **Physics-Informed GAN**
- **File:** `physics_gan.ipynb`
- **Description:** Enhances GAN training by incorporating domain-specific constraints such as smoothness, non-negativity, and realistic thermal bounds.
- **Use Case:** Generating physically meaningful battery temperature profiles using deep learning with physics-based regularization.

---

## Key Features Across Notebooks
- Simulated or real-world style data preparation
- LSTM or CNN-based architectures suitable for time-series
- Proper normalization and preprocessing routines
- Modular training loops with monitoring
- Visualization of generated vs. real sequences

---

## Requirements
- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- scikit-learn

Install dependencies with:
```bash
pip install torch numpy matplotlib scikit-learn
```

---

## License
These notebooks are shared for academic and educational use under the MIT License.

---

## Contact
Chahinez Ounoughi  
Tallinn University of Technology  
✉️ chahinez.ounoughi@taltech.ee
