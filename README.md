# 🌀 Supernova Cosmology – Hubble Parameter Estimation

## Overview

This project uses the **Pantheon+SH0ES Type Ia supernova dataset** to estimate the **Hubble constant (H₀)** and explore the expansion history of the Universe.
By fitting a flat ΛCDM cosmological model to the observed supernova data, we compare late-universe measurements of H₀ with the early-universe result from **Planck18**, investigate residuals, and calculate the estimated **age of the Universe**.

---

## Contents

* **2\_hubble\_parameter.ipynb** → Main Jupyter notebook with full analysis, code, plots, and answers.

---

## Requirements

Install the following Python libraries before running the notebook:

```bash
pip install jupyter astropy
```

```bash
pip install numpy pandas matplotlib scipy
```

---

## How to Run

1. Download the dataset `Pantheon+SH0ES.dat` and place it in your working directory.
2. Open `2_hubble_parameter.ipynb` in Jupyter Notebook / JupyterLab.
3. Run all cells (`Kernel > Restart & Run All`).
4. The notebook will produce:
   * **Plot 1:** Hubble Diagram (Redshift vs Distance Modulus)
   * **Plot 2:** Hubble Diagram with Model Fit
   * **Plot 3:** Residuals vs Redshift

---

## Key Results

* **Estimated Hubble constant:**
  $H_0 = 72.97 \pm 0.26$ km/s/Mpc
* **Comparison with Planck18:**
  Planck18 = $67.4 \pm 0.5$ km/s/Mpc, and this reveals the **Hubble tension**
* **Age of the Universe:**
  \~12.36 Gyr (for Ωₘ = 0.3)
* **Residuals:**
  Well-centered around zero, with slightly higher scatter at extreme redshifts

---

## References

- [Summer School Day 02: Basics of Python (B2) - Indian Space Academy](https://www.youtube.com/watch?v=c4w3MNkfYvo)
- [Summer School Day 03: Fits File Handling (B1) - Indian Space Academy](https://www.youtube.com/watch?v=kxoQ7VRBqi0)
- [ISA Summer School 2025 Github & Session files](https://github.com/supremeKAI40/ISA-Summer_School_2025)
- [Pantheon+SH0ES Dataset Download](https://github.com/PantheonPlusSH0ES/DataRelease/blob/main/Pantheon%2B_Data/4_DISTANCES_AND_COVAR/Pantheon%2BSH0ES.dat)  
- [Planck 2018 Cosmological Parameters](https://arxiv.org/abs/1807.06209)  
- [Astropy Constants Documentation](https://docs.astropy.org/en/stable/constants/)  
- [Scipy `curve_fit`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html)  
---
