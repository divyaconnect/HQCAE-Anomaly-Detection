# HQCAE-Anomaly-Detection

<h1 align="center">Hybrid Quantum-Classical Autoencoder for Anomaly Detection</h1>

<h3 align="center">Enhanced with Quantum Entanglement Intelligence and Dual-Space Analytics</h3>

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-AI-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

### Quantum-Assisted Dual-Space Autoencoder for Intelligent Anomaly Detection

A hybrid quantum-classical framework for anomaly detection using deep learning and quantum entanglement analysis.

---

### Overview

This project presents a Quantum-Assisted Dual-Space Autoencoder designed to improve anomaly detection by combining classical feature reconstruction and quantum latent-space analysis.

The framework learns normal data patterns and identifies anomalous observations through a hybrid scoring mechanism that utilizes both reconstruction error and quantum subsystem behavior. It pairs interactive exploration, experiment notebooks, and Google Gemini-assisted insights with a local deterministic fallback mode so core analysis continues reliably even during network latency or cloud API quota disruptions.

---

### Research Motivation

Traditional autoencoders rely primarily on reconstruction error for anomaly detection. However, subtle anomalies may remain hidden in complex feature spaces.

This research explores whether quantum representations and entanglement characteristics can provide additional information for improving anomaly detection performance.

---

### Architecture Summary

```text
Input Features
      │
      ▼
Classical Encoder
(16 → 8 → 4)
      │
      ▼
Quantum Embedding
      │
      ▼
4-Qubit Variational Circuit
      │
 ┌────┴────┐
 ▼         ▼
Entropy   Measurements
Analysis
 └────┬────┘
      ▼
Classical Decoder
(4 → 8 → 16)
      │
      ▼
Reconstructed Output
      │
      ▼
Hybrid Anomaly Score
---
      
### Core Components

#### Classical Encoder

Feature compression
Dimensionality reduction
Latent representation learning

---

#### Quantum Processing Layer

Angle Embedding
Strongly Entangling Layers
Variational Quantum Gates
Pauli-Z Measurements

---

#### Reconstruction Module

Decoder network
Input reconstruction
Residual error computation

---

#### Entropy Analysis

Von Neumann Entropy
Quantum correlation measurement
Latent anomaly characterization

---

### Hybrid Anomaly Scoring

The final anomaly score combines classical and quantum information:
```text
Score = Reconstruction Error

+ λ × Quantum Entropy

```

This enables anomaly detection in both classical and quantum feature spaces.

---

### Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

![PennyLane](https://img.shields.io/badge/PennyLane-Quantum-1B1F23?style=for-the-badge)

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## Experimental Evaluation

The framework is evaluated using multivariate datasets and analyzed through:

- 📈 ![Training Loss](https://img.shields.io/badge/Metric-Training%20Loss%20Curves-2563EB?style=flat-square) **Training Loss Curves**
- ✅ ![Validation](https://img.shields.io/badge/Metric-Validation%20Performance-16A34A?style=flat-square) **Validation Performance**
- 📉 ![ROC](https://img.shields.io/badge/Metric-ROC%20Analysis-7C3AED?style=flat-square) **ROC Analysis**
- 🎯 ![Precision & Recall](https://img.shields.io/badge/Metric-Precision%20%26%20Recall-D97706?style=flat-square) **Precision & Recall**
- 🧩 ![Confusion Matrix](https://img.shields.io/badge/Metric-Confusion%20Matrix-DB2777?style=flat-square) **Confusion Matrix**
- 🌀 ![Entropy](https://img.shields.io/badge/Metric-Entropy%20Distribution-0891B2?style=flat-square) **Entropy Distribution Analysis**
- 🔍 ![Feature Error](https://img.shields.io/badge/Metric-Feature--Level%20Error-DC2626?style=flat-square) **Feature-Level Reconstruction Error**

---

### Repository Structure

```text

Quantum-Anomaly-Detection/

│

├── assets/

│ ├── demo.mp4

│ └── hqca-pictures.pdf

├── docs/

│ └── HCQA-Research-paper.pdf

├── notebooks/

│ ├── hqcae_experiment.ipynb

│ └── HQCAE-anomalyquantum.ipynb

├── requirements.txt

├── LICENSE

├── README.md

└── .gitignore

---

### Installation

git clone https://github.com/yourusername/Quantum-Anomaly-Detection.git

cd Quantum-Anomaly-Detection

pip install -r requirements.txt

```

---

### Live Demo

🎥 Project Demonstration

[https://me-l.co/brrk57qs](https://me-l.co/x1zvkeam)


### Run Project

```bash

jupyter notebook hqcae_experiment.ipynb

```

---

### Future Scope

| Domain | Focus Area | Planned Enhancement |
| :--- | :--- | :--- |
| ⚛️ ![Hardware](https://img.shields.io/badge/Quantum%20Hardware-8E75B2?style=flat-square) | **Real Quantum Hardware Implementation** | Executing variational circuits on real NISQ quantum processors with noise mitigation |
| 🚀 ![Scale](https://img.shields.io/badge/Scalability-007EC6?style=flat-square) | **Large-Scale Anomaly Detection** | Scaling high-dimensional feature encoding for massive streaming datasets |
| 🏭 ![Industry](https://img.shields.io/badge/Industrial%20IoT-2EA44F?style=flat-square) | **Industrial Monitoring Applications** | Real-time predictive maintenance and telemetry fault detection |
| 🧠 ![QXAI](https://img.shields.io/badge/Explainable%20AI-F37626?style=flat-square) | **Quantum Explainable AI** | Mapping Von Neumann entropy and qubit measurements to human-readable insights |
| 🛡️ ![Security](https://img.shields.io/badge/Cybersecurity-E05D44?style=flat-square) | **Cybersecurity Analytics** | Zero-day intrusion and subtle behavioral threat detection |

---

### Author

**Divya**

B.Tech Computer Science & Technology (AI & ML)

---

### License

MIT License 
