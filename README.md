# 🧠 ThyroCheck AI – Thyroid Nodule Cancer Detection with Explainable AI

## 🚀 Overview

**ThyroCheck AI** is a full-stack medical AI system that detects **thyroid nodule cancer** from ultrasound images using deep learning.
The system integrates **Explainable AI (Grad-CAM)** to provide visual interpretability and generates **real-time clinical reports** for enhanced decision support.

---

## 🎯 Key Features

* 🔍 **Thyroid Cancer Detection** using Deep Learning (FibonacciNet-based CNN)
* 🧠 **Explainable AI (Grad-CAM)** for visualizing diagnostic regions
* 📊 **Confidence Scoring & Classification Output**
* 🖼️ **Real-time Image Upload & Processing**
* 📄 **Automated Clinical Report Generation (DOCX)**
* ⚡ **FastAPI Backend + Interactive Frontend UI**

---

## 🏗️ System Architecture

```
Ultrasound Image
        ↓
Preprocessing
        ↓
FibonacciNet CNN Model
        ↓
Prediction (Benign / Malignant)
        ↓
Grad-CAM Heatmap
        ↓
Frontend Visualization + Report Generation
```

---

## 🧪 Model Details

* **Architecture:** FibonacciNet-based CNN
* **Task:** Binary Classification (Benign vs Malignant)
* **Accuracy:** 85%
* **AUC Score:** 0.91
* **Input:** Thyroid Ultrasound Images

---

## 🧠 Explainable AI

Grad-CAM is used to:

* Highlight **regions influencing predictions**
* Improve **model transparency**
* Assist clinicians in **interpreting AI decisions**

---

## 🛠️ Tech Stack

### 🔹 Backend

* FastAPI
* TensorFlow / Keras
* Hugging Face Hub (Model Hosting)

### 🔹 Frontend

* HTML, CSS (Glassmorphism UI)
* JavaScript (Fetch API)

### 🔹 Tools

* Grad-CAM
* PIL / NumPy
* Python-docx (Report Generation)

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/thyrocheck-ai.git
cd thyrocheck-ai
```

### 2. Create Virtual Environment

```bash
uv venv
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
uv pip install -r requirements.txt
```

### 4. Run Application

```bash
uvicorn app:app --reload
```

### 5. Open in Browser

```
http://localhost:8000
```

---

## 📸 Demo Features

* Upload ultrasound image
* Get prediction (Benign / Malignant)
* View confidence score
* Visualize Grad-CAM heatmap
* Download clinical report


---

## 🚀 Future Improvements

* 🌐 Deploy on cloud (AWS / Render)
* 🧠 Add segmentation (U-Net)
* 📊 Confidence visualization charts
* 🧾 PDF report preview
* 🏥 Integration with hospital systems

---

## 👨‍💻 Author

**Swapnil Banerjee**


---

## ⭐ Acknowledgements

* TensorFlow
* Hugging Face
* FastAPI
* Medical Imaging Research Community
* FibonacciNet Architecture

---

## 📌 Disclaimer

This project is for **research and educational purposes only** and should not be used as a substitute for professional medical diagnosis.
