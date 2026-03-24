# scalable-gpr-sketching
Scalable Gaussian Process Regression via ridge leverage score sketching with theoretical guarantees. Provides efficient approximation of predictive mean, variance, and marginal likelihood, with strong empirical performance on large-scale datasets.

# Sketch-GPR: Scalable Gaussian Process Regression via Sketching

## 📄 Paper

**On Sketching for Gaussian Process Regression with New Statistical Guarantees**
*Jayesh Malaviya, Rachit Chhaya, Anirban Dasgupta, Supratim Shit*

Published in **Transactions on Machine Learning Research (TMLR), 2026**

---

## 🚀 Overview

Gaussian Process Regression (GPR) provides powerful uncertainty-aware predictions but suffers from cubic computational complexity.

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

```bash
python experiments/run_protein.py
```

You can modify configurations in the `configs/` folder to run different datasets and settings.

---

## 📌 Citation

If you find this work useful, please consider citing:

```bibtex
@article{malaviya2026sketchgpr,
  title={On Sketching for Gaussian Process Regression with New Statistical Guarantees},
  author={Malaviya, Jayesh and Chhaya, Rachit and Dasgupta, Anirban and Shit, Supratim},
  journal={Transactions on Machine Learning Research},
  year={2026}
}
```
We will update the repository soon with more clean and complete codebase. 
---

## 📜 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

This work was supported by SERB-MATRICS and SERB-CRG research grants.

