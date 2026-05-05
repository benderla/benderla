# Benderla — ML Systems & Data Science Portfolio

I build and operate production-grade machine learning systems end-to-end — from raw data and modeling to deployment, monitoring, and continuous improvement.

My focus is on solving real-world problems using data, designing systems that work under imperfect conditions, and ensuring models deliver reliable outcomes in production environments.

---

## What I Do

* Build ML systems using Python, scikit-learn, and real-world datasets
* Design data pipelines and feature engineering workflows for messy, imbalanced data
* Deploy models using FastAPI and Docker for production-ready inference
* Evaluate models using precision-recall tradeoffs, threshold tuning, and performance diagnostics
* Implement monitoring strategies to detect drift, degradation, and system failures

---

## Core Portfolio

### 🔹 Network Attack Detection (Flagship)

End-to-end anomaly detection system using ~700K network flow records (CIC-IDS2017 dataset)

* Isolation Forest model with threshold tuning for imbalanced classification
* Feature engineering on network behavior (duration, packet rate, ports, flow stats)
* Model evaluation using precision, recall, F1, ROC, and PR curves
* FastAPI inference service with Docker containerization

→ Demonstrates full ML lifecycle: data → model → API → deployable system

---

### 🔹 ML Model Monitoring

Framework for detecting model drift, performance degradation, and operational risk

* Monitors prediction distributions and data drift signals
* Evaluates ongoing model performance against baseline expectations
* Defines alerting strategies for production ML systems

→ Demonstrates how to operate ML systems after deployment

---

### 🔹 ML System Launch (TPM + Operator View)

End-to-end launch plan for deploying an anomaly detection system in production

* Defines milestones, risks, dependencies, and execution strategy
* Balances tradeoffs between accuracy, latency, and scalability
* Includes failure scenarios, rollout strategy, and operational readiness

→ Demonstrates ownership of ML systems from build to production

---

## Technical Stack

* Python (pandas, numpy, scikit-learn)
* FastAPI (model serving)
* Docker (containerization)
* Data analysis & visualization (matplotlib, seaborn)

---

## Focus

I am focused on building ML systems that are:

* Practical — work on real, messy data
* Measurable — evaluated with the right metrics
* Deployable — usable beyond a notebook
* Operable — monitored and maintained over time

---

## Repository Structure

* `network-attack-detection` → end-to-end ML system (flagship)
* `ml-model-monitoring` → monitoring and observability
* `ml-anomaly-detection-system-launch` → production execution strategy
* `ml-platform-architecture` → supporting architecture (archived)

---
