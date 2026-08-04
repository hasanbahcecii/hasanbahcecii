<div align="center">
  <h1>Hasan Bahçeci</h1>
  <h3>Computer Engineering Student · AI/ML Engineer in Training</h3>
  <p>Building end-to-end AI systems — from architecture design to production deployment</p>

  <a href="https://www.linkedin.com/in/hasanbahceci">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:hasan.bahceci021@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://hasanbahceci-voice-assistant.hf.space">
    <img src="https://img.shields.io/badge/🎙️ Voice Demo-FF4B4B?style=for-the-badge"/>
  </a>
</div>

---

## 🚀 Featured Projects

### 🎯 UAV Target Selection — TEKNOFEST Combat UAV
**PyTorch · Transformer · GNN · TCN · Multi-Architecture Benchmark**

[![GitHub](https://img.shields.io/badge/GitHub-uav--target--selection-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/uav-target-selection)

Benchmarked 4 architectures (TCN, TCN+GlobalContext, GNN+GRU, Full Transformer) on 15,000 synthetic multi-UAV combat scenarios (9 behaviour types, 1.18M labelled samples). Full Transformer achieved **91.5% val accuracy vs. 82.2% TCN baseline (+9.3 pp)** — selected for ground station deployment. Dual-attention: temporal (6-timestep history) + spatial (inter-UAV).

`91.5% val acc · 137K params · <1ms GPU inference · 1 Hz telemetry budget`

---

### 🎙️ LLM-Powered Voice Assistant
**STT → LLM (OpenAI / Hugging Face) → TTS · Wake Word · 14-module architecture**

[![Live Demo](https://img.shields.io/badge/Live_Demo-HuggingFace-yellow?style=flat-square)](https://hasanbahceci-voice-assistant.hf.space)
[![GitHub](https://img.shields.io/badge/GitHub-voice__assistant-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/voice_assistant)

End-to-end voice assistant with dual-backend LLM (OpenAI + Hugging Face), real-time speech recognition, neural TTS, and wake-word detection — modular architecture enabling hot-swap provider with no code change.

---

### 🔧 Sensor Fault Detection — LSTM-FCN
**PyTorch · SMOTE · Failure Analysis · UCI SECOM**

[![GitHub](https://img.shields.io/badge/GitHub-sensor--fault--detection-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/sensor-fault-detection)

Dual-branch LSTM-FCN on 590-sensor semiconductor manufacturing data (93/7 class imbalance). Leakage-free pipeline: split → scale → SMOTE (train only). Diagnosed model limitation via PCA (13% variance) + t-SNE — faulty samples lack separable structure; RF baseline confirmed dataset-level root cause.

`Macro F1: 0.55 vs dummy baseline 0.48 · 266K params · Failure analysis documented`

---

### 🌫️ Air Quality Forecasting — LSTM Pipeline
**PyTorch · FastAPI · Streamlit · Multivariate Time-Series**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Streamlit-FF4B4B?style=flat-square)](https://air-quality-prediction-ehb9tnezgfquw42hvveumr.streamlit.app)
[![API](https://img.shields.io/badge/API-Render-46E3B7?style=flat-square)](https://air-quality-api-wuxw.onrender.com/docs)
[![GitHub](https://img.shields.io/badge/GitHub-air--quality--prediction-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/air-quality-prediction)

Forecasts hourly NO₂ from 72-step multivariate sensor stream (UCI Air Quality). Full pipeline: imputation → normalization → sliding-window → LSTM → FastAPI → Streamlit UI.

`MAE: 46.65 μg/m³ vs persistence baseline ~72 μg/m³ (~35% improvement)`

---

### 🐾 Cat vs Dog Classifier — Transfer Learning + ONNX
**TensorFlow · MobileNetV2 · ONNX Runtime · Streamlit**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Streamlit-FF4B4B?style=flat-square)](https://hasanbahcecii-cat-dog-image-classifier-app-gtgtuq.streamlit.app)
[![GitHub](https://img.shields.io/badge/GitHub-cat--dog--classifier-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/cat-dog-image-classifier-cnn)

MobileNetV2 transfer learning (2-phase: frozen extraction → fine-tuning) with data augmentation. Exported to ONNX for CPU-efficient inference.

`Test Accuracy: 98.70% · ~14ms CPU inference (ONNX)`

---

## 🛠️ Tech Stack

**AI / Machine Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

`CNN · RNN · LSTM · GRU · TCN · GNN · Transformer · Transfer Learning · Time-Series · Computer Vision`

**Deployment & Tools**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

`REST APIs · OpenAI API · Hugging Face · ONNX Runtime`

**Mobile & Embedded**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

`C/C++ · STM32 · Arduino · Verilog · Flutter (Dart)`

---

## 🎓 Education

**Erzurum Technical University** — B.Sc. Computer Engineering (English) · 2022–2027  
**Politechnika Lubelska** — Erasmus+ Exchange · Oct 2024 – Feb 2025
