# GSNR-Based FoM for Estimating Span Lengths of Optical Fibers

[![Language: Python](https://img.shields.io/badge/language-Python%203-blue.svg?logo=python)](https://www.python.org/)
[![DOI](https://img.shields.io/badge/DOI-placeholder-blue.svg)](https://doi.org/your-doi-here)

**Authors:** V. Ivanov, J. Downie, L. Galdino, Y. Mikhalkova (2025)

## 📋 Project Overview
This repository implements the formulas described in the paper:

**“GSNR-Based FoM for Estimating Span Lengths of Different Optical Fibers to Achieve Equal Transmission Capacity.”**

The main notebook **`GSNR_based_FOM.ipynb`**:
- Reproduces all figures from the paper.
- Implements GSNR-based models and analytical approximations.
- Compares ISRS-GN, GN, and FoM-based approaches for span length estimation.

---

## ✅ Features
- **GSNR Calculation** using:
  - GN model
  - Analytical FoM-based model
- **Span Length Optimization** for equal transmission capacity.
- **Visualization** of GSNR vs span length and improvement metrics.

---

## 📂 Repository Structure
```
├── GSNR_based_FOM.ipynb        # Main Jupyter notebook
├── ISRS_GN_GSNR_dB_1550nm.csv  # Input data for ISRS-GN model
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## 🔧 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/corning-incorporated/fiber_optic_fom.git
cd fiber_optic_fom
pip install -r requirements.txt
```

---

## 📄 Requirements
Ensure the following Python packages are installed:
```
numpy
scipy
pandas
matplotlib
scienceplots
```

---

## ▶️ Usage
Open the notebook in Jupyter:
```bash
jupyter notebook GSNR_based_FOM.ipynb
```
Run all cells to:
- Compute GSNR for different fiber types.
- Generate plots reproducing figures from the paper.
- Compare span length improvements.

---

## 📊 Outputs
The notebook generates:
- **GSNR vs Span Length** plots for three models.
- **Equal-GSNR Span Lengths** comparison.
- **Span Length Improvement** charts.

---

## 📚 Reference
If you use this code, please cite:
```
Ivanov V., Downie J., Galdino L., Mikhalkova Y.
"GSNR-Based FoM for Estimating Span Lengths of Different Optical Fibers to Achieve Equal Transmission Capacity", 2025.
DOI: [insert DOI here]
```

---

## 🛠 Contributing
Feel free to submit issues or pull requests to improve the code or documentation.

---

## 📜 License
Copyright 2025. Corning Incorporated. All rights reserved.

This software may only be used in accordance with the identified license(s).  
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,  
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
