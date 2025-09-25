# 🧠 Brain Network Analysis

This repository contains the **Brain Network Analysis** project conducted as part of our final-year B.Tech in Information Technology at **Government Engineering College, Barton Hill**.

The project investigates how **Temporal Lobe Epilepsy (TLE)** alters brain connectivity using **fMRI** and **T1-weighted MRI** data. By applying **complex network theory** and graph-theoretic measures, the study identifies connectivity differences between healthy individuals and epilepsy patients.

---

## 📌 Problem Statement

Temporal Lobe Epilepsy (TLE) originates in the hippocampus and affects memory, emotions, and behavior. Traditional diagnostic tools often miss subtle changes in connectivity. This project applies **advanced neuroimaging analysis** to identify differences in brain networks between healthy and epileptic subjects, focusing on metrics like clustering coefficient, modularity, density, and path length.

---

## 🎯 Objectives

* Identify alterations in structural connectivity and key brain regions affected by epilepsy.
* Analyze network metrics (clustering, density, modularity, path length).
* Validate network analysis methods to interpret cognitive and emotional impacts of TLE.

---

## 📚 Scope

This project combines **CONN** (for network construction) and **Gephi** (for visualization) to:

* Provide a **statistical and graphical framework** for brain network analysis.
* Compare **healthy vs. TLE-affected** brain connectivity.
* Offer insights into epilepsy-related changes in the hippocampus, amygdala, and Default Mode Network (DMN).

⚠️ **Note**: The original dataset (from SCTIMST, Kerala, India) cannot be shared due to privacy restrictions. Users may instead test workflows with **synthetic or public datasets** (e.g., from [OpenNeuro](https://openneuro.org/)).

---

## 🛠️ Tools & Technologies

* **MATLAB** (SPM12, CONN Toolbox v22)
* **Gephi** (network visualization)
* **Python** (NetworkX, NumPy, Pandas, Matplotlib)

---

## 📂 Dataset

The dataset used in this project was obtained from **SCTIMST, Kerala, India**, and consists of **10 subjects** – 5 healthy controls and 5 epilepsy patients. It includes **T1-weighted structural MRI** and **functional MRI (fMRI)** scans in NIfTI (.nii) format. Due to privacy and ethical restrictions, the original dataset cannot be shared publicly. However, the workflow can be replicated using **synthetic data** or **open-access neuroimaging datasets** available on [OpenNeuro](https://openneuro.org/).

---

## 📂 Repository Structure

```
brain-network-analysis/
│
├── notebooks/        # Jupyter notebooks for analysis
├── results/          # Example output figures and graphs
├── docs/             # Documentation, diagrams, and project images
│
├── README.md         # Project overview
├── requirements.txt  # Dependencies
└── .gitignore        # Ignore unnecessary files
```

---

## 📊 Key Results

* **Epileptic patients** show:

  * Higher clustering, density, and modularity
  * Shorter path lengths (faster signal spread → seizure propagation)
  * Stronger hippocampus and amygdala connectivity (linked to memory & emotional changes)
  * Altered DMN activity (possible compensatory reorganization)

📈 These findings suggest that epilepsy leads to **hyperconnected local circuits** but **disrupted global communication**, impacting cognition and emotions.

---

## 📈 Network Metrics Studied

* **Global & Local Efficiency**
* **Betweenness Centrality**
* **Average Path Length**
* **Clustering Coefficient**
* **Graph Density**
* **Modularity**
* **Degree**

---

## 👩‍💻 Authors

* **Megha Rajeev P** (IDK21IT029)
* Amina I R (IDK21IT008)
* Arya Satheesh (IDK21IT013)
* Glory Susan Thomas (TRV21IT024)
* **Guide**: Prof. Rendhir R Prasad

---
This project is for academic purposes only and is not open for reuse.
---

