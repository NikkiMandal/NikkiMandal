# Hi, I'm Nikita Mandal 👋

**Machine Learning & Systems Engineer | Edge AI, Sensor Fusion, Signal Processing & Robust Deployment**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg)](https://www.linkedin.com/in/nikitamandal03/) 
[![Email](https://img.shields.io/badge/Email-Contact_Me-success.svg)](mailto:mandal.n@northeastern.edu)

I am an ML Engineer focused on deploying high-performance deep learning models to resource-constrained edge devices. My engineering philosophy is rooted in systems reliability: before specializing in AI, I spent two years designing **SIL4 safety-critical Train Control Systems at Alstom**. I don't just optimize for accuracy in a notebook; I optimize for fail-safe execution, deterministic latency, and real-world edge cases.

Currently wrapping up my MS in Electrical and Computer Engineering at **Northeastern University** and recently engineered real-time radar/camera fusion pipelines at **Aura Intelligent Systems**. 

*I am actively seeking full-time roles where I can build reliable, deployment-ready AI systems.*

---

## 🛠️ Technical Arsenal

* **Core Machine Learning:** PyTorch, Deep Learning (CNNs/ViTs), Time-Series Forecasting, Signal Processing (DSP)
* **Edge AI & C++ Deployment:** C++, Python, ONNX Runtime, TensorRT, CUDA, TFLite, Model Compression & Pruning
* **Computer Vision & Sensor Fusion:** OpenCV, YOLO, Point Cloud Library (PCL), Radar/Camera Fusion, ROS/ROS2
* **MLOps & Infrastructure:** GCP (Vertex AI), Docker, Apache Airflow, MLflow, CI/CD (GitHub Actions), FastAPI, CMake
* **Robust Systems Engineering:** SIL4 Safety-Critical Architecture, Hardware-in-the-Loop (HIL), Adversarial Robustness

## 🚀 Featured Work

### 1. High-Performance C++ Inference Engine for Edge Robotics
Engineered a custom C++ inference engine from scratch to bypass Python's GIL for real-time robotic perception.
* **Impact:** Increased throughput by **1.36x (15.0 FPS to 45.0 FPS)** on CPU-only hardware and implemented zero-copy memory management.
* **Tech Stack:** `C++`, `ONNX Runtime`, `OpenCV`, `CMake`, `YOLO11`
* [View Repository ->](#) *https://github.com/NikkiMandal/yolo11-cpp-inference*

### 2. Real-Time Spectral Signal Decoder (BrainStorm Hackathon - 2nd Place)
Designed a real-time causal streaming pipeline to classify high-density ECoG sensor data for brain-computer interfaces.
* **Impact:** Won 2nd place by compressing the model size to **150KB (16x reduction)** to fit wearable memory limits, while hitting a strict **35ms latency budget**.
* **Tech Stack:** `PyTorch`, `Signal Processing (FFT)`, `TorchScript JIT`, `Model Compression`
* [View Repository ->](#) *https://github.com/NikkiMandal/neural-decoder-challenge*

### 3. End-to-End MLOps Pipeline for Continuous Deployment
Architected an automated ML pipeline on the cloud for time-series anomaly detection and forecasting.
* **Impact:** Reduced manual retraining by **80%** using statistical data drift triggers (K-S test) and accelerated release cycles by **40%** via containerized CI/CD workflows.
* **Tech Stack:** `GCP (Vertex AI)`, `Apache Airflow`, `Docker`, `FastAPI`, `MLflow`
* [View Repository ->](#) *https://github.com/NikkiMandal/Ozone_Level_Detection*

### 4. Adversarial Robustness in Safety-Critical Vision Models
Investigated edge-case failures and safety vulnerabilities in deploying deep learning models for high-reliability systems.
* **Impact:** Engineered a hybrid defense strategy recovering **>75% robustness** under rigorous PGD sensor attacks, proving Vision Transformers are **11% more resilient** to localized noise than CNNs.
* **Tech Stack:** `Vision Transformers (ViT)`, `CNNs`, `Adversarial ML (PGD/Patch)`
* [View Repository ->](#) *https://github.com/NikkiMandal/Adversarial-attacks-and-defence-on-Medical-Data*

---
