# DeepFake Detective

A modular AI/ML project focused on detecting manipulated media using a combination of spatial and frequency-based analysis.

---

## Overview

This project explores deepfake detection through two parallel approaches:

- CNN-based image analysis to capture visual inconsistencies  
- FFT-based feature extraction with a lightweight ML classifier  

The outputs are combined to produce a final prediction, with scope for adding explainability and graph-based analysis.

---

## Pipeline

Input  
→ CNN model → spatial score  
→ FFT + ML → frequency score  
→ Fusion → final prediction  
→ (optional) visualization and analysis  

---

## Modules

- CNN Model — image-based detection  
- Frequency Model — FFT + ML features  
- Fusion — combines model outputs  
- XAI (planned) — interpretability  
- Graph Analysis (planned) — propagation logic  

---

## Structure

models/  
processing/  
core/  
utils/  
evaluation/  
algorithms/  

---

## Tech Stack

Python, TensorFlow, NumPy, Scikit-learn, Pandas  

---

## Team Work (Initial Split)

- CNN Model — model development and training  
- Frequency Model — FFT processing and ML classifier  
- Fusion & XAI — combining outputs and visualization  
- Graph Analysis — search algorithms and data insights  

---

## Status

Day 0 — initial setup and module planning  
