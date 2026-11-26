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
<div align="center">
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
