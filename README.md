# 🌿 Virtual E-Tongue: AI-Enabled Quality Assessment of Medicinal Herbs

## 📌 Background

In **Ayurveda** and other traditional medicine systems, **Rasa (taste)** is a fundamental criterion for identifying, classifying, and determining the therapeutic value of medicinal herbs.  

While effective for centuries, this approach is subjective, relying on human perception and expertise, often leading to variability and inconsistency.  

In today’s global herbal market, ensuring **authenticity, quality, and standardization** is critical due to:
* Adulteration of raw materials
* Batch-to-batch phytochemical variations
* Demand for reliable, evidence-based products

Modern technologies like **electronic tongues (e-tongues)** and spectroscopic profiling (NIR, Raman, UV-Vis, LC-MS), when combined with **AI/ML models**, provide a way to objectively classify herbs, detect adulteration, and assess quality with high precision.  

---

## 🎯 Problem Statement

We aim to design and develop a **sensor-integrated AI-enabled system** for **objective quality assessment** of marketed herbal samples.

The device/system will include:
* ✅ **Multi-sensor e-tongue array** (simulated with pH, conductivity, TDS, bitter markers).
* ✅ **Threshold detection module** for quantifying minimum perceptible concentrations.
* ✅ **Phytochemical integration** (via RDKit descriptors) to link taste signatures with chemical constituents.
* ✅ **AI/ML models** (Random Forest, PCA, SVM) for classification and adulteration detection.
* ✅ **Visualization layer (dashboard/web app)** for real-time alerts and quality scores.

---

## ⚡ Expected Solution

* **Portable hardware prototype** (Arduino/ESP32-based e-tongue + sensors).
* Calibration using authenticated herbal datasets + ML training.
* **Smart alerts & decision support** for detecting adulteration/substandard quality.
* Centralized/cloud database of herbal taste & phytochemical fingerprints.
* Applicability across Ayurvedic pharmacopeia, herbal industry QC, academic research, and regulatory bodies.

---

## 🛠️ Current Progress (Hackathon Build)

| Feature | Status | Notes |
| :--- | :--- | :--- |
| **Synthetic Sensor Dataset** (pH, Saltiness, TDS, Bitter marker) | ✅ Done | Expanded simulated feature set. |
| **Threshold Detection Logic** (Above/Below MDC) | ✅ Done | Taste perceivability check added. |
| **RDKit Integration** (Phytochemical Descriptors: Glucose, Caffeine, Citric Acid) | ✅ Done | Linked phytochemicals to tastes. |
| **Machine Learning Pipeline** (Random Forest, PCA) | ✅ Done | ML classifier trained on fused data. |
| **GitHub Setup** | ✅ Done | Repository structure and collaboration. |
| **Sensor Hardware Integration** | 🟡 In Progress | Currently simulated only. |
| **Dashboard/Web app** (Streamlit/Flask) | ❌ To Do | Visualization layer for demo. |
| **Workflow Diagram + Documentation** | ❌ To Do | To be added for presentation. |

---

## 🚀 Roadmap (Hackathon Phases)

This README doubles as our progress tracker.

| Phase | Description | Status |
| :--- | :--- | :--- |
| **Phase 1** | Understanding & Scoping | ✅ Completed |
| **Phase 2** | Hardware Prototype (Simulated Sensors) | ✅ Completed |
| **Phase 3** | **Threshold Detection** (Define MDCs) | ✅ Completed |
| **Phase 4** | **AI/ML Classification** (Adulteration Detection, PCA Visualization) | ✅ Completed |
| **Phase 5** | Phytochemical Profiling (More compounds + correlation) | 🟡 In Progress |
| **Phase 6** | **Dashboard/App** (Streamlit/Flask Interface) | ❌ To Do |

---
