# Ap-Star-Evolution
This project aims to estimate the main-sequence lifetimes of chemically peculiar Ap stars and predict when they will evolve into white dwarfs. Using a catalog of Ap star data, we derive stellar masses, estimate evolution times using stellar evolution models, and visualize the distribution of these timescales.
# 🌟 Ap-Star Evolution to White Dwarfs

This project predicts **when chemically peculiar Ap stars will evolve into white dwarfs**, based on their estimated masses. We utilize stellar evolution models to compute main-sequence lifetimes and visualize the distribution of evolution timescales.

---


## 🔭 Overview

Ap stars (peculiar A-type stars) are interesting due to their strong magnetic fields and chemical peculiarities. Understanding when they transition to white dwarfs helps in tracing stellar evolution and enriching stellar population models.

This notebook-based analysis:

- Estimates stellar main-sequence lifetimes from mass.
- Identifies stars that have evolved into white dwarfs.
- Visualizes the estimated evolution times.

---


## 📁 Project Structure
Ap-Star-Evolution
*Ap_Star_White_Dwarf_Prediction.ipynb # Main Jupyter notebook with analysis and plots

*Ap_stars_catalog.csv # Input catalog of Ap stars

*read_mist_models.py # MIST model reader script (if used)

*README.md # This file

---


## 🚀 Getting Started 

 📦 Installation:

pip install pandas numpy matplotlib

jupyter notebook Ap_Star_White_Dwarf_Prediction.ipynb


📊 Visualization Preview:

The notebook generates histograms showing the estimated time (in Gyr) it takes for Ap stars to become white dwarfs:
X-axis: Estimated time to become a white dwarf.
Y-axis: Number of Ap stars.


📚 Data Source:

Ap star data is derived from published astronomical catalogs (e.g., Gaia DR3, Simbad, LAMOST).
Lifetime estimations use approximations based on stellar evolution theory (e.g., MIST models).


📄 Acknowledgements:

MIST Stellar Evolution Models
Gaia Mission
LAMOST Spectroscopic Survey
pandas, numpy, and matplotlib for powering the analysis


Author:

VEDHA DARSHNI.S.R.
Astrophysics enthusiast | Data Science enthusiast | Data Analysis enthusiast |




