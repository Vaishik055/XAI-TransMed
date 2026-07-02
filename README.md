# 🧠 XAI-TransMed
### Explainable Alzheimer's Disease Detection using Hybrid CNN-Transformer

XAI-TransMed is an Explainable Artificial Intelligence (XAI) based web application for early Alzheimer's Disease detection from 3D MRI brain scans. The system combines a Hybrid CNN-Transformer architecture with Grad-CAM and Attention Rollout to provide accurate predictions along with visual explanations, improving transparency and supporting clinical decision-making.

---

## 🚀 Features

- 🧠 Alzheimer's Disease Detection from 3D MRI (.nii/.nii.gz)
- 🔍 Hybrid CNN-Transformer architecture
- 📈 Explainable AI using:
  - Grad-CAM
  - Attention Rollout
- 📊 Confidence Score Prediction
- 🌐 Modern React + Flask Web Interface
- ⚡ Real-time MRI Analysis
- 🖼️ Interactive Explainability Heatmaps

---

## 🏗️ System Architecture

```
MRI Scan
     │
     ▼
Preprocessing
     │
     ▼
Hybrid CNN
(Local Feature Extraction)
     │
     ▼
Vision Transformer
(Global Context Learning)
     │
     ▼
Classification
     │
     ▼
Explainability
(Grad-CAM + Attention Rollout)
     │
     ▼
Prediction Dashboard
```

---

## 📸 Screenshots

### Landing Page

> Add screenshot here

```
frontend/public/images/landing.png
```

### Prediction Dashboard

> Add screenshot here

```
frontend/public/images/dashboard.png
```

### Explainability Map

> Add screenshot here

```
frontend/public/images/explainability.png
```

---

## 🛠 Tech Stack

### Frontend
- React
- Vite
- JavaScript
- CSS

### Backend
- Flask
- Python

### AI / Deep Learning
- PyTorch
- MONAI
- Torchvision
- NumPy
- OpenCV
- Nibabel
- Scikit-Learn

### Explainable AI
- Grad-CAM
- Attention Rollout

---

## 📂 Project Structure

```
XAI-TransMed
│
├── ai/
│   ├── ViT/
│   ├── v2/
│   └── best_model.pth
│
├── backend/
│   ├── app.py
│   ├── uploads/
│   ├── results/
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── research_code/
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Vaishik055/XAI-TransMed.git

cd XAI-TransMed
```

---

### Backend Setup

```bash
cd backend

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python app.py
```

Backend runs at:

```
http://localhost:8080
```

---

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## 🧪 Model Performance

| Metric | Value |
|---------|-------|
| Validation Accuracy | **93.18%** |
| Recall (Sensitivity) | **90.48%** |
| Specificity | **94.03%** |
| F1 Score | **86.36%** |
| MCC | **81.98%** |

---

## 📈 Explainable AI

The model provides interpretable predictions using:

- Grad-CAM for highlighting important local brain regions.
- Transformer Attention Rollout for global attention visualization.
- Hybrid Explainability Maps combining CNN and Transformer explanations.

This improves transparency and helps clinicians understand model decisions.

---

## 📄 Research

This repository contains the implementation developed as part of our research on explainable Alzheimer's Disease detection using deep learning.

---

## 👨‍💻 Author

**Vaishik Goudampally**

- GitHub: https://github.com/Vaishik055
- LinkedIn: https://linkedin.com/in/vaishikgoudampally

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
