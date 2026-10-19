<div align="center">

# Henry Paolo Alfaro Sotil

### Physics → Data Science

**Data Analyst · Junior Data Scientist · Scientific Computing**

<a href="https://github.com/elbrujo325">
  <img src="https://img.shields.io/badge/GitHub-elbrujo325-181717?style=for-the-badge&logo=github" alt="GitHub"/>
</a>
<a href="https://www.linkedin.com/">
  <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
</a>

<br>

**Python · SQL · Statistics · Machine Learning · Scientific Computing**

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=539BF5&center=true&vCenter=true&width=700&lines=Physics+%E2%86%92+Data+Science;Scientific+Computing+%7C+Machine+Learning;Time+Series+%7C+Simulation+Data+%7C+Financial+Data;Building+reproducible+quantitative+models" alt="Typing animation"/>

</div>

---

## 👨‍🔬 About Me

I am a **Physics student at Universidad Nacional Mayor de San Marcos (UNMSM)** transitioning into Data Analytics and Data Science.

My background in physics has trained me to work with **mathematical models, numerical methods, statistical analysis, computational experiments, and scientific data**.

I apply this quantitative approach to different types of real-world and research datasets:

- 📈 **Financial time series**
- 🌌 **Astronomical observations**
- 🌊 **Large multidimensional oceanographic data**
- 🧲 **MHD simulation data**
- 🤖 **Machine learning and statistical modeling**

My goal is to work in **Data Analytics / Data Science**, using Python, statistics and quantitative reasoning to solve real problems.

📍 Lima, Peru · 🌎 Open to remote opportunities

---

# 🧰 Technical Stack

<div align="center">

### 🐍 Programming & Data

<img src="https://skillicons.dev/icons?i=python,sqlite,git,linux,docker" height="48"/>

<br><br>

### 📊 Data Science & Machine Learning

<img src="https://skillicons.dev/icons?i=tensorflow,pytorch" height="48"/>

<br>

<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/SciPy-0C55A5?style=for-the-badge&logo=scipy&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>

<br><br>

### 🧮 Mathematics & Scientific Computing

<img src="https://img.shields.io/badge/SymPy-3B5526?style=for-the-badge&logo=sympy&logoColor=white"/>
<img src="https://img.shields.io/badge/SciPy-Scientific_Computing-0C55A5?style=for-the-badge&logo=scipy&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-Numerical_Analysis-013243?style=for-the-badge&logo=numpy&logoColor=white"/>

<br>

**Numerical Methods · Statistical Modeling · Optimization · Differential Equations · Computational Physics**

<br><br>

### 📈 Visualization & Multidimensional Data

<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white"/>
<img src="https://img.shields.io/badge/Seaborn-Data_Visualization-4C72B0?style=for-the-badge"/>
<img src="https://img.shields.io/badge/xarray-Multidimensional_Data-1F77B4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Dask-Parallel_Computing-FDA061?style=for-the-badge&logo=dask&logoColor=black"/>

</div>

---

# 🚀 Featured Projects

## 🌌 01 · Kerr–Newman × Event Horizon Telescope

**[tesis-kerr-newman-eht](https://github.com/elbrujo325/tesis-kerr-newman-eht)**

> Can a weakly charged black-hole model produce a measurable difference in the observed shadow?

My undergraduate thesis project combines **analytical physics, numerical modeling, real observational data and statistical validation**.

### 🔬 Method

```text
Kerr–Newman model
       ↓
Photon sphere
       ↓
Effective shadow radius
       ↓
Visibility model
       ↓
EHT interferometric data
       ↓
χ² statistical comparison
       ↓
Detectability analysis
```

### Key components

- Exact Kerr–Newman photon-sphere formulation
- Weak-charge parameterization
- Thin-ring + Gaussian visibility model
- χ² fitting of interferometric amplitudes
- Sgr A* and M87* EHT datasets
- Symbolic verification with SymPy
- Automated tests with Pytest
- Reproducible Python package structure

### Results

| Source | Model | δ | R_eff [μas] | χ²ν |
|---|---:|---:|---:|---:|
| Sgr A* | Schwarzschild | 0.000 | 26.14 | 123.28 |
| Sgr A* | **Kerr–Newman** | **0.290** | **24.79** | **118.96** |
| M87* | Schwarzschild | 0.000 | 21.00 | 67.21 |
| M87* | Kerr–Newman | 0.100 | 20.64 | 77.95 |

**Important:** the Sgr A* improvement does **not** constitute a high-significance detection of black-hole charge; the inferred shadow change is smaller than the dominant systematic uncertainty. The M87* comparison performs worse under the simplified model.

**Stack:** Python · NumPy · SciPy · SymPy · Astropy · ehtim · Matplotlib · Pytest

---

## 📈 02 · Small-Cap Quantitative ML

**[smallcap-quant-ml](https://github.com/elbrujo325/smallcap-quant-ml)**

End-to-end machine-learning pipeline for quantitative analysis of hourly small-cap equity data.

```text
EDA
 ↓
Feature Engineering
 ↓
Triple-Barrier Labeling
 ↓
Random Forest
 ↓
Feature Selection
 ↓
Decision Tree
 ↓
Trading Rules
 ↓
Backtest
 ↓
Chronological OOS Validation
```

### What I implemented

- Financial time-series EDA
- ~20 technical/statistical features
- Triple-barrier labeling
- Random Forest feature importance
- Shallow Decision Trees
- Rule extraction
- Risk-aware backtesting
- Chronological 70/30 train-test separation
- Performance and drawdown analysis

**Stack:** Python · pandas · NumPy · scikit-learn

> Research/backtesting project. Results are historical simulations and are not presented as evidence of future performance.

---

## 🌊 03 · GLORYS Ocean Data

**[projecto-glorys](https://github.com/elbrujo325/projecto-glorys)**

Large-scale oceanographic analysis of **GLORYS12V1 reanalysis data** focused on the Peruvian coast.

### Dataset

**1993–2026 · 1/12° resolution · monthly · depths to ~1942 m**

### Analysis

- 🌡️ SST climatology and anomalies
- 🧂 Salinity
- 🌊 Ocean currents
- 📉 Point time series
- 📐 Vertical profiles
- 🗺️ Cross-sections
- 📊 Spectral analysis / FFT
- ⚡ Lazy multidimensional processing with Dask

**Stack:** Python · xarray · Dask · NumPy · Matplotlib · Cartopy

This project demonstrates working with **large multidimensional scientific datasets beyond conventional tabular workflows**.

---

## 🧲 04 · FLASH-MHD Analysis

**[FLASH-MHD-Analysis](https://github.com/elbrujo325/FLASH-MHD-Analysis)**

Analysis toolkit for **HDF5 output from FLASH magnetohydrodynamic simulations of accretion disks**.

### Quantities analyzed

- Disk scale height H(t)
- Density-weighted vertical structure
- Kurtosis
- Probability density distributions
- Kinetic energy
- Magnetic energy
- Thermal energy
- Gravitational energy

**Stack:** Python · NumPy · SciPy · h5py · Matplotlib · Fortran

Used to investigate simulation structure, turbulence and energy evolution in MHD accretion-disk models.

---

# 🧠 What I Work With

<div align="center">

| Domain | Applications |
|---|---|
| 📊 **Data Analysis** | EDA · statistical analysis · data quality · visualization |
| 🤖 **Machine Learning** | feature engineering · model selection · validation |
| 📈 **Time Series** | financial series · climatology · spectral analysis |
| 🌌 **Scientific Data** | simulations · observational data · multidimensional datasets |
| 🧮 **Quantitative Modeling** | numerical methods · optimization · mathematical models |
| 🐍 **Python** | scientific computing · data pipelines · reproducible analysis |

</div>

---

# 💼 Experience

### Data Analyst — HSE Golden
**Nov 2025 – Apr 2026**

- Analyzed hourly financial time series and small-cap equity datasets.
- Performed exploratory and statistical analysis.
- Developed quantitative features and risk metrics.
- Evaluated systematic strategies using chronological train/test separation.
- Built visualizations and analytical reports to support quantitative decision-making.

### Physics & Mathematics Teacher
**Apr 2026 – Present**

- Teach physics and mathematics through quantitative and problem-solving approaches.
- Translate complex mathematical and physical concepts into structured explanations.
- Develop analytical reasoning and computational problem-solving skills.

---

# 🔬 Research

### Undergraduate Thesis — UNMSM

**Perturbative Analysis of Photon Spheres and Shadow Detectability in Weakly Charged Kerr–Newman Spacetimes**

Research combining:

**General Relativity · Perturbation Theory · Numerical Methods · Statistical Fitting · EHT Data**

### Scientific Computing

- Magnetohydrodynamic simulations with FLASH
- Computational physics
- Numerical differential equations
- Scientific visualization
- Reproducible computational experiments

---

# 📚 Education

**B.Sc. Physics — Universidad Nacional Mayor de San Marcos**

Faculty of Physical Sciences

Current focus:

`Data Science · Machine Learning · Statistical Analysis · Scientific Computing`

---

# 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=elbrujo325&show_icons=true&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true" height="170"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=elbrujo325&layout=compact&hide_border=true&langs_count=8" height="170"/>

</div>

---

# 🧭 Current Focus

```text
Advanced SQL
      +
Statistical Analysis
      +
Machine Learning
      +
Data Visualization
      +
Production-oriented Python
```

---

<div align="center">

### Physics gives me the models.
### Data gives me the evidence.

<br>

**Open to Data Analyst and Junior Data Scientist opportunities.**

📍 Lima, Peru · 🌎 Remote

</div>
