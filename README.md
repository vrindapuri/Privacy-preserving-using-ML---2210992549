# PFed-HE: Privacy-Preserving Federated Learning with Homomorphic Encryption

A secure and privacy-preserving Federated Learning (FL) framework integrating **Homomorphic Encryption (HE)** and **Differential Privacy (DP)** for protected decentralized machine learning.

## Overview

PFed-HE is a research-oriented implementation of Federated Learning that ensures sensitive client data never leaves local devices while still enabling collaborative model training.

This project combines:

- Federated Learning using **FedAvg**
- CKKS-based Homomorphic Encryption using **TenSEAL**
- Differential Privacy using Gaussian Noise
- Dynamic Key Rotation
- Batch Processing Optimization

The notebook demonstrates how encrypted model updates can be aggregated securely without exposing raw client data.

---

## Features

- Federated Averaging (FedAvg)
- Homomorphic Encryption (CKKS Scheme)
- Differential Privacy Integration
- Secure Aggregation
- Key Rotation Mechanism
- Batch Processing Optimization
- Privacy vs Accuracy Analysis
- Performance Comparison with Baseline FL

---

## System Architecture

```text
Clients
   ↓
Local Training
   ↓
Encrypted Model Updates
   ↓
Secure Server Aggregation
   ↓
Global Model Update
   ↓
Clients Receive Updated Model
