# Solving the Time-Dependent Schrödinger Equation using Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Physics-Informed Neural Networks for the Quantum Harmonic Oscillator**

---

## 📘 What is this repository?

This repository contains the full code and analysis accompanying the project _Solving the Time-Dependent Schrödinger Equation using Machine Learning_. The goal of this study is to use a Physics-Informed Neural Network (PINN) to learn the dynamics of quantum systems—specifically, the quantum harmonic oscillator.

The model is trained to solve the time-dependent Schrödinger equation (TDSE) using only the physical laws governing the system and no explicit supervision. It achieves high accuracy in predicting both coherent and breathing state dynamics.

📝 **You can read the full report [here](https://hdl.handle.net/2445/222442)**

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE.txt](LICENSE.txt) file for details.

When using this code, please:  
- Retain the original copyright notice  
- Attribute by linking back to this repository (e.g., `Solving the TDSE using Machine Learning by Elizabeth Birch Hardwick`)

---

## 📁 Repository structure

```
📄 breathing_mode.ipynb       # PINN solving the breathing mode dynamics
📄 coherent_state.ipynb       # PINN solving the coherent state dynamics
📄 tests.ipynb                # Extensive tests of PINN components and behaviour
📄 requirements.txt           # List of required Python packages
📄 LICENSE.txt                # MIT License
📄 README.md                  # This file
```

---

## 📓 Usage

Clone the repository and install dependencies:

```bash
git clone https://github.com/elizabethbirchhardwick/TDSE_ML.git
cd TDSE_ML
pip install -r requirements.txt
```

Launch the Jupyter notebooks:

```bash
jupyter notebook coherent_state.ipynb
jupyter notebook breathing_mode.ipynb
```

Inside the notebooks, you'll find:

- 📈 **Full implementation of a Physics-Informed Neural Network for solving the TDSE**
- 🧠 **Real and imaginary wavefunction reconstruction via log-magnitude and phase**
- 🧪 **Coherent state dynamics with high-precision overlap (up to 0.99999)**
- 🌬️ **Breathing mode simulation showing generalisation capabilities**
- 🧪 **Validation and diagnostics in `tests.ipynb`**

All code cells are pre-run for convenience, but you are encouraged to experiment!

---

## 💬 Support

For questions or suggestions, feel free to reach out:

📧 **elizabethbirchhardwick@gmail.com**  
🚀 Or open an issue on [GitHub](https://github.com/elizabethbirchhardwick/TDSE_ML/issues)
