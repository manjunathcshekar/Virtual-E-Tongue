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
* ✅ **Multi-sensor e-tongue array** to detect basic taste modalities (sweet, sour, salty, bitter, pungent, astringent).
* ✅ **Threshold detection module** for quantifying minimum perceptible concentrations.
* ✅ **Phytochemical integration** (simulated via RDKit/descriptors) for linking taste signatures with chemical constituents.
* ✅ **AI/ML models** (Random Forest, SVM, PCA) for classification and adulteration detection.
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
| **Simulated Taste Dataset** (Tulsi, Turmeric, Adulterated) | ✅ Done | |
| **RDKit Integration** (Phytochemical Descriptors) | ✅ Done | Initial setup complete. |
| **Machine Learning Pipeline** (Random Forest, PCA) | ✅ Done | Initial model training/visualization complete. |
| **GitHub Setup** | ✅ Done | Repository structure and collaboration guidelines established. |
| **Threshold Detection Logic** | ❌ To Do | Critical for setting minimum quality standards. |
| **Sensor Integration** (pH, EC, TDS - or simulated) | 🟡 In Progress | Currently using simulated values. |
| **Dashboard/Web app** (Streamlit/Flask) | ❌ To Do | Visualization layer for demo. |
| **Workflow Diagram + Documentation** | ❌ To Do | |

---

## 🚀 Roadmap (Hackathon Phases)

This README doubles as our progress tracker.

| Phase | Description | Status |
| :--- | :--- | :--- |
| **Phase 1** | Understanding & Scoping | ✅ Completed |
| **Phase 2** | Hardware Prototype (Simulated/Fallback) | 🟡 In Progress |
| **Phase 3** | **Threshold Detection** (Define MDCs) | ❌ To Do |
| **Phase 4** | **AI/ML Classification** (Refine Models, Adulteration Detection) | 🟡 In Progress |
| **Phase 5** | Phytochemical Profiling (RDKit Correlation) | ❌ To Do |
| **Phase 6** | **Dashboard/App** (Build Streamlit/Flask Interface) | ❌ To Do |

