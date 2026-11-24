# HQCAE-Anomaly-Detection
Hybrid Quantum-Classical Autoencoder (HQCAE) for Anomaly Detection
A research project proposing a novel Hybrid Quantum-Classical Autoencoder (HQCAE) for anomaly representation and detection. The framework combines classical neural networks and quantum machine learning techniques to identify anomalies using both reconstruction error and quantum entanglement characteristics.

Overview
Traditional autoencoders detect anomalies through reconstruction error alone. This project enhances anomaly detection by incorporating quantum information theoretic measures, specifically Von Neumann Entanglement Entropy, to capture hidden quantum-space patterns that may not be observable in classical feature space.

The proposed HQCAE architecture leverages a parameterized quantum circuit as the latent bottleneck, creating a dual-space anomaly detection mechanism.

Key Features
Hybrid Quantum-Classical Autoencoder Architecture
4-Qubit Parameterized Quantum Circuit
Quantum Latent Space Representation
Von Neumann Entanglement Entropy Analysis
Dual-Space Anomaly Scoring
End-to-End Training using PyTorch and PennyLane
Synthetic Multivariate Anomaly Detection Benchmark
Architecture
Input Data (16 Features)
          │
          ▼
 Classical Encoder
 (16 → 8 → 4)
          │
          ▼
  Quantum Latent Space
      (4 Qubits)
          │
          ▼
 Parameterized Quantum Circuit
          │
          ▼
 Classical Decoder
 (4 → 8 → 16)
          │
          ▼
 Reconstructed Output
          │
          ▼
Dual-Space Anomaly Scoring
Methodology
Classical Encoding
The input feature vector is compressed into a low-dimensional latent representation using fully connected neural network layers.

Quantum Processing
Latent features are embedded into a 4-qubit quantum system using rotation-based angle encoding techniques. Strongly entangling quantum layers generate expressive quantum representations.

Dual-Space Anomaly Detection
The final anomaly score combines:

Classical Reconstruction Error (MSE)
Quantum Entanglement Entropy
Formula:

S_dual(x) = MSE(x) + β × EntanglementEntropy(x)

where β = 0.15.

Technologies Used
Python
PyTorch
PennyLane
NumPy
Matplotlib
Jupyter Notebook
Experimental Results
Metric	Performance
ROC-AUC	0.97
Accuracy	92%+
Anomaly Detection	Improved through dual-space analysis
Quantum Metric	Von Neumann Entanglement Entropy
The results demonstrate that incorporating quantum entanglement information provides additional anomaly-related signals beyond traditional reconstruction error.

Repository Structure
HQCAE-Anomaly-Detection/
│
├── assets/
│   └── experimental_results.png
│
├── paper/
│   └── HQCAE_Research_Paper.pdf
│
├── hqcae_experiment.ipynb
├── requirements.txt
├── README.md
└── .gitignore
Installation
git clone https://github.com/yourusername/HQCAE-Anomaly-Detection.git

cd HQCAE-Anomaly-Detection

pip install -r requirements.txt
Run
Open the notebook:

jupyter notebook hqcae_experiment.ipynb
Research Contribution
This work introduces a hybrid anomaly detection framework that combines:

Classical reconstruction-based learning
Quantum latent representation learning
Entanglement entropy-based anomaly characterization
Dual-space anomaly decision making
Future Work
Testing on real-world industrial datasets
Deployment on quantum hardware
Larger qubit architectures
Quantum-enhanced latent optimization
Author
Divya

B.Tech Computer Science and Technology (AI & ML)

Citation
If you use this work, please cite:

Hybrid Quantum-Classical Autoencoder (HQCAE) for Anomaly Representation and Detection
Author: Divya
Year: 2026
License
MIT License
