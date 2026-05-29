# CHEOPS Secondary Eclipse Analysis

This repository contains the Python notebooks and analysis framework developed as part of an M.Sc. project.  
The project investigates secondary eclipse observations of hot Jupiters using data from the CHaracterising ExOPlanet Satellite (CHEOPS), with a focus on the systems TOI1518b and HD202772Ab.

---

## 📄 Project Overview

The code implements a Bayesian light-curve analysis framework performing:

- CHEOPS light-curve loading and visualization  
- Data preprocessing and sigma clipping  
- Diagnostic analysis of instrumental parameters  
- Detrending of instrumental systematics  
- Secondary eclipse modeling using `batman`  
- Bayesian parameter estimation with nested sampling using `dynesty`  
- Joint fitting of multiple observational visits  
- Bayesian model comparison between detrending models  
- Posterior visualization and corner plotting  

The analysis aims to retrieve eclipse depths and orbital parameters while accounting for correlated instrumental noise present in CHEOPS photometry.

---

## 🔭 Targets Analysed

- TOI1518b  
- HD202772Ab  

---

## 🧠 Development Notes

This code was written in **Python 3.11** using standard scientific libraries:

`numpy`, `scipy`, `matplotlib`, `astropy`, `batman-package`, `dynesty`, and `corner`.


## 📁 Repository Contents

The repository includes notebooks for:

- Individual visit fitting  
- Joint fitting analyses  
- Systematics testing and detrending model comparison  
- RMS-binning analysis  
- Posterior analysis and visualization  

---

## 📚 Data Source

CHEOPS observations were obtained through the CHEOPS Data Reduction Pipeline (DRP) and ESA archival products.

---
