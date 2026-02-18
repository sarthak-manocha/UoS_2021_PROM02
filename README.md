# Master’s Dissertation – Drowsiness Detection

**A Comparative Study into Feature Extraction/Descriptor Methods for Improving Supervised Machine Learning**  
*University of Sunderland – MSc Data Science (2021)*

---

## 🧠 Project Overview

This repository houses the code, data, and artifacts from my Master’s Dissertation, which investigates the impact of feature extraction techniques — especially **Histogram of Oriented Gradients (HOG)** — on supervised machine learning performance for **drowsiness detection** from visual data.

The aim was to determine whether enhanced features improve classification accuracy over baseline approaches, and to implement a working prototype that demonstrates the solution in action.

---

## 📂 Repository Contents
📦 (root)
┣ 📂 MRL_DS_CAT
┣ 📂 MRL_DS_RAW
┣ 📂 PROM02_Prototype
┣ PROM02_01_Exploratory-Data-Analysis.ipynb
┣ PROM02_02_Classification-Models.ipynb
┣ PROM02_03_Deep-Learning.ipynb
┣ model_SVM_HOG.sav
┣ README.md

- **MRL_DS_RAW** – Raw dataset used for preprocessing and modeling  
- **MRL_DS_CAT** – Categorised or preprocessed dataset files  
- **PROM02_Prototype** – Real-time prototype code (Haar Cascades + model)  
- **Notebooks** – EDA, classification pipelines, deep learning experiments  
- **model_SVM_HOG.sav** – Trained SVM model with HOG feature descriptor

---

## 📘 Key Notebooks

| Notebook | Purpose |
|----------|---------|
| **PROM02_01_Exploratory-Data-Analysis.ipynb** | Explore and preprocess raw data |
| **PROM02_02_Classification-Models.ipynb** | Train and evaluate traditional ML models (e.g., SVM + HOG) |
| **PROM02_03_Deep-Learning.ipynb** | Deep learning experiments and comparisons |

---

## 🧠 Model Artifact

- **`model_SVM_HOG.sav`** – Serialized SVM model trained using HOG feature extraction, used by the prototype for real-time predictions.

---

## 🚀 Prototype Demonstration

The live prototype demonstrates a real-time drowsiness detection system using:

- **OpenCV Haar Cascades** for face and eye detection
- The trained **HOG-enhanced SVM model** to predict eye-state probability
- Logic to alert the user if eyes are closed for ~4–5 seconds

This shows how the trained model can be used practically in driver monitoring scenarios.

---

## 🔗 Related Resources

- 📄 **Written Dissertation** – [Full academic report](https://drive.google.com/file/d/1RHRxLgpEWVRc_iIDe3_GiC6y68NbHs-Q/view?usp=sharing)  
- 📄 **Dissertation Appendix** – [Supporting material and raw data](https://drive.google.com/file/d/19QCD9ncC60_qiFzTyP3DTuqAe-_U-Qjm/view?usp=drive_link)  
- 🎥 **Prototype Demonstration** – [Video walkthrough of the live detection system](https://drive.google.com/drive/folders/1GU3uEWR35FBmc50c5EWP1W9BHpxL99Ia?usp=sharing)

---

## 📦 Setup & Dependencies

To run the notebooks and prototype locally:

### Requirements

Ensure you have Python 3.7+ installed and required libraries:

```bash
pip install opencv-python numpy scikit-learn scikit-image matplotlib jupyter
