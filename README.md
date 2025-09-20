# Duality AI – Astronaut Safety Object Detection  

## 📌 Overview  
This project was developed for the **HackWithHyderabad Hackathon (Duality AI Problem Statement)**.  
We built an **AI-powered object detection system** that ensures astronaut safety inside space stations by detecting **7 critical safety objects in real-time**:  

- 🟢 Oxygen Tank  
- 🔵 Nitrogen Tank  
- 🩹 First Aid Box  
- 🔔 Fire Alarm  
- ⚡ Safety Switch Panel  
- ☎️ Emergency Phone  
- 🔴 Fire Extinguisher  

The system is trained on the provided dataset and integrated into a **web application** for real-time predictions.  

---

## 🛠 Tech Stack  
- **Model:** YOLOv8 (Ultralytics, PyTorch backend)  
- **Backend:** Flask + PocketBase (API service)  
- **Frontend:** React.js (user interface)  
- **Storage:** JSON + PocketBase DB  
- **Deployment:** Local/Web App  

---

## 📂 Repository Structure  

This is the **main repository**. The full project is organized into three parts:  

1. **Model Training Repository** → [🔗 Model Repo Link]  
   - Contains YOLOv8 training scripts, config files, and trained weights (`best.pt`).  
   - Instructions for reproducing training are in the model repo’s README.  

2. **Application Repository** → [🔗 Application Repo Link]  
   - Flask + React web app.  
   - Runs inference using the trained model.  
   - Instructions for running the app are in the app repo’s README.  

3. **Google Drive Dataset & Outputs** → [🔗 Google Drive Link]  
   - Contains full dataset (~12GB), training logs, and `runs/` outputs.  

---

## ⚡ Training Summary  
- **Base Model:** yolov8s.pt  
- **Epochs:** 60  
- **Image Size:** 640  
- **Batch Size:** 16  
- **Optimizer:** AdamW  
- **Results (Train5 – 60 Epochs):**  
  - Precision: **0.919**  
  - Recall: **0.727**  
  - mAP50: **0.800**  
  - mAP50-95: **0.668**  

## Weights

The best model weights are saved at:

runs/detect/train5/weights/best.pt

---

## 📑 Submission Files

- **Final Report (PDF/DOCX):** [Download Here](https://drive.google.com/your-report-link)  
- **Final PPT (Hackathon Presentation):** [Download Here](https://drive.google.com/your-ppt-link)  

---

## ⚙️ Tech Stack

- **YOLOv8 (Ultralytics)**
- **Python 3.13, PyTorch 2.7.1**
- **React + Pocketbase** (Web App)
- **Google Drive + GitHub** (Storage and Version Control)

---

## 🚀 How to Reproduce

Follow individual instructions in each repo:

- [Model Repo README](https://github.com/YourUsername/Model-Repo)  
- [Application Repo README](https://github.com/YourUsername/Application-Repo)  

---

## 🏆 Hackathon Context

- Organized as part of **HackWithHyderabad**.  
- Submission includes code, trained models, application, PPT, and detailed report.  

---
