# Master's Dissertation – Drowsiness Detection

**A Comparative Study into Feature Extraction/Descriptor Methods for Improving Supervised Machine Learning**  
*University of Sunderland – MSc Data Science (2021)*

---

## 🧠 Project Overview

This repository contains the code and supporting materials for my **Master’s Dissertation** project, which investigates the effectiveness of feature extraction techniques in improving supervised machine learning performance for **drowsiness detection**.

The study compares traditional supervised learning models enhanced with feature extraction methods — most notably **Histogram of Oriented Gradients (HOG)** — and evaluates their impact in detecting signs of drowsiness from visual data.

---

## 🛠️ Solution Summary

The core solution implemented in this project:

- Written primarily in **Python**
- Uses a **Supervised Learning model** — *Support Vector Machine (SVM)*
- Enhanced with **Histogram of Oriented Gradients (HOG)** feature extraction/descriptor to improve classification accuracy
- Includes **experimental evaluation and comparative analysis** based on feature extraction techniques

---

## 🎯 Key Features

### 📌 Machine Learning Model

- **Model:** Support Vector Machine (SVM)
- **Feature Extraction:** Histogram of Oriented Gradients (HOG)
- **Goal:** Improve performance for detecting signs of drowsiness based on facial image features

---

## 🧪 Prototype Demonstration

A simple prototype application demonstrates how the model can be used in practice:

- Utilises **Haar Cascades** for:
  - Face detection
  - Eye detection
- Runs on a **live webcam video feed**
- Predicts probability of eye state (i.e., percentage of eye openness)
- If eyes remain closed for **4–5 seconds**, the prototype triggers an alert

This real-time prototype shows how the model could be deployed for driver monitoring or fatigue detection systems.

---

## 📁 Repository Contents

| Folder/File | Description |
|-------------|-------------|
| `model/` | Python implementation of the SVM + HOG model |
| `prototype/` | Code for the live video prototype using Haar Cascades |
| `data/` | Sample images, datasets, and preprocessed features |
| `notebooks/` | Jupyter Notebooks with experimentation and analysis |
| `results/` | Evaluation results, graphs, and model comparisons |
| `dissertation/` | Written dissertation and appendix documents |

---

## 📚 Related Resources

- 📄 **Written Dissertation** – [Full academic report](https://drive.google.com/file/d/1RHRxLgpEWVRc_iIDe3_GiC6y68NbHs-Q/view?usp=sharing)
- 📄 **Dissertation Appendix** – [Supporting material and raw data](https://drive.google.com/file/d/19QCD9ncC60_qiFzTyP3DTuqAe-_U-Qjm/view?usp=drive_link)
- 🎥 **Prototype Demonstration** – [Video walkthrough of the live detection system](https://drive.google.com/drive/folders/1GU3uEWR35FBmc50c5EWP1W9BHpxL99Ia?usp=sharing)

(*Links to these resources can be attached here if available.*)

---

## 📦 Quick Start

### Requirements

Make sure you have the following installed:

- Python 3.7+
- OpenCV
- NumPy
- scikit-learn
- scikit-image
- matplotlib

Install dependencies via:

```bash
pip install -r requirements.txt
