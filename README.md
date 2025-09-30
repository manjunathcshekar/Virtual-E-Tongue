# Virtual E-Tongue: AI-Enabled Herbal Quality Assessment

## 🔹 Overview
In Ayurveda and traditional medicine, **Rasa (taste)** is crucial for identifying and assessing medicinal herbs.  
However, human taste-based evaluation is **subjective, inconsistent, and cannot be used for mass quality control**.  

This project develops a **virtual and AI-enabled electronic tongue (e-tongue) prototype** that:  
- Simulates taste profiles of herbs  
- Integrates chemical descriptors (via RDKit)  
- Uses machine learning to detect adulteration and classify herbs objectively  

This approach bridges **traditional Ayurvedic principles with modern scientific validation**.

---

## 🔹 Problem Statement
We are addressing the following challenges in herbal quality assessment:

1. ⚠️ **Subjective human taste** – human perception varies across experts  
2. ❌ **No direct human testing allowed** – for safety and scalability  
3. ⚠️ **Adulteration risk** – widespread adulteration and inconsistency in marketed herbal samples  

---

## 🔹 Project Objectives
- Build a **sensor-simulated dataset** representing taste, aroma, and special characteristics  
- Integrate **chemical descriptors** using RDKit for each compound  
- Train **machine learning models** to classify herbs and detect adulteration  
- Provide a **visualization and dashboard-ready output** for real-time quality monitoring  

---

## 🔹 Expected Solution
💡 **Virtual E-Tongue Prototype**:

- Multi-sensor simulation: taste (sweet, bitter, pungent), aroma, special features  
- RDKit chemical descriptors: molecular weight, LogP, TPSA, H-bond donors/acceptors  
- ML model (Random Forest) for classification and adulteration detection  
- 2D & 3D PCA visualizations  
- Future: integrate **web dashboard** for monitoring and decision support  

---

## 🔹 Innovation & Uniqueness
- Combines **AI/ML** with **traditional Ayurvedic principles**  
- Uses **chemical + sensor feature fusion** for precise and objective quality assessment  
- Simulates an **electronic tongue system** without expensive hardware for early prototyping  
- Can be extended to **real sensor integration and cloud-based monitoring**  

---

## 🔹 Installation

1. Clone the repo:
```bash
git clone https://github.com/manjunathcshekar/Virtual-E-Tongue.git
cd Virtual-E-Tongue
