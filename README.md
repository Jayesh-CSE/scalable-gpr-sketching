

# NOTE: We will update this repository shortly with a clean, well-documented, and complete codebase.


# Sketch-GPR: Scalable Gaussian Process Regression via Sketching

## 📄 Paper

**On Sketching for Gaussian Process Regression with New Statistical Guarantees**
*Jayesh Malaviya, Rachit Chhaya, Anirban Dasgupta, Supratim Shit*

Published in **Transactions on Machine Learning Research (TMLR), 2026**

---

## 🚀 Overview

Gaussian Process Regression (GPR) provides powerful uncertainty-aware predictions but suffers from cubic computational complexity.

# scalable-gpr-sketching
Scalable Gaussian Process Regression via ridge leverage score sketching with theoretical guarantees. Provides efficient approximation of predictive mean, variance, and marginal likelihood, with strong empirical performance on large-scale datasets.

This repository contains the official implementation of a **sketching-based framework for scalable GPR**, using **ridge leverage score sampling** to construct efficient Nyström approximations with strong theoretical guarantees.

---

## ✨ Key Contributions

* 📌 First theoretical guarantees for:

  * Predictive mean approximation
  * Predictive variance approximation
  * Negative log marginal likelihood (NLML)
* ⚡ Scalable kernel approximation via ridge leverage score sketching
* 📊 Strong empirical performance across real-world datasets
* 💾 Improved memory–accuracy trade-offs compared to RFF and other baselines

---

## 📊 Results

Our method achieves superior performance in terms of predictive accuracy and uncertainty calibration compared to standard baselines such as SVGP, IterGP, Nyström variants, and Random Fourier Features.

---

## ⚙️ Installation

```bash
git clone https://github.com/Jayesh-CSE/scalable-gpr-sketching.git
cd scalable-gpr-sketching
pip install -r requirements.txt
```

---

## ▶️ Running Experiments

---

## 📌 Citation

If you find this work useful, please consider citing:

```bibtex
@article{
malaviya2026on,
title={On Sketching for Gaussian Process Regression with New Statistical Guarantees},
author={Jayesh Malaviya and Rachit Chhaya and Anirban Dasgupta and Supratim Shit},
journal={Transactions on Machine Learning Research},
issn={2835-8856},
year={2026},
url={https://openreview.net/forum?id=NmwrhyuVEu},
note={}
}
```

## 📜 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

This work was supported by SERB-MATRICS and SERB-CRG research grants.

