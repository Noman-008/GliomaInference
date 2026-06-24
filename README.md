# GliomaInference


## Project Overview

This project develops and calibrates a **mechanically coupled reaction–diffusion (Mech-RD)** tumor growth model using **Bayesian inference**. The framework integrates tumor biology with tissue mechanics to better capture realistic tumor evolution.

MRI tumor data from different rats are used to infer key parameters:

* Elastic modulus (**E**)
* Diffusivity (**D**)
* Proliferation rate (**G**)

Model performance is evaluated using:

* **DICE coefficient** (shape overlap)
* **Normalized Tumor Area (NTA)**

---

## 📁 Repository Structure

```
GliomaInference/
│
├── BayesianInference/        → Core modeling, and Inference
├── W05_data/                 → Rat data and mesh
```

---

## 🔍 Folder Descriptions

### `BayesianInference`

Contains the complete computational framework:

* Forward models (Mech-RD basically the Hyperelastic setup)
* Bayesian inference (MAP, LA)

### `W05_data`

Contains the data:

* MRI dataset
* FE Mesh

📌 Detailed instructions and module descriptions are provided in:

```
BayesianInference/README.md
W05_data/READNE.md
```
