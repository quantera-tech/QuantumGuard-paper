# QuantumGuard: Quantum Malware Detection Framework

A research-driven project for applying **Quantum Convolutional Neural Networks (QCNNs)** and hybrid quantum-classical models to malware detection in Windows PE binaries.

---

## Overview

This repository implements a novel, distributed QCNN architecture that analyzes malware binaries by splitting them into critical PE sections, encoding each for quantum processing, and classifying them using both quantum and classical ensemble methods. The design is optimized for NISQ-era quantum devices.

---

## Key Features

- **Distributed QCNNs:**  
  Five independent 8-qubit QCNNs, each specialized for a PE section (.text, .data, .rdata, .rsrc, .reloc).

- **Quantum Data Encoding:**  
  Supports amplitude, qubit, dense qubit, hybrid direct, and hybrid angle encoding.

- **Hybrid Integration:**  
  Combines quantum outputs with classical models (XGBoost, Random Forest, neural networks).

- **NISQ-Ready:**  
  Resource-efficient, modular design for current quantum hardware.

- **Comprehensive Benchmarking:**  
  Evaluates accuracy, resource use, robustness, and hardware compatibility.

