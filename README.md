<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hasanbahcecii/hasanbahcecii/main/banner-dark.svg">
  <img src="https://raw.githubusercontent.com/hasanbahcecii/hasanbahcecii/main/banner-light.svg" width="100%" alt="Hasan Bahçeci"/>
</picture>
<br/>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasanbahceci)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:hasan.bahceci021@gmail.com)
[![Demo](https://img.shields.io/badge/Live_Demo-FF4B4B?style=flat-square&logo=huggingface&logoColor=white)](https://hasanbahceci-voice-assistant.hf.space)
 
<br/>
> Autonomous systems from perception to actuation —
> ROS2, sensor fusion, edge inference, and embedded firmware.
 
</div>
---
 
## ⚡ Projects
 
<table>
<tr>
<td width="50%" valign="top">
### 🔧 ArduCore `WIP`
**AVR · Register-level C · FSM · Binary Protocol**
 
Sub-system controller on ATmega328P — no `delay()`, no `analogWrite()`, no Servo lib. PCINT-driven echo capture, ISR-based sensor averaging, binary host-command framing, 5-state FSM.
 
Roadmap → custom USART driver · Timer1 Fast PWM · WDT · **STM32 port**
 
[![GitHub](https://img.shields.io/badge/GitHub-arducore-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/arducore)
 
</td>
<td width="50%" valign="top">
### 🎯 UAV Target Selection `private · TEKNOFEST`
**PyTorch · Transformer · GNN · TCN**
 
4-architecture benchmark on 1.18M labeled multi-UAV scenarios. Full Transformer: **91.5% val acc** vs 82.2% TCN baseline. Dual-attention: temporal + spatial. Selected for ground station deployment.
 
`137K params · <1ms GPU inference`
 
</td>
</tr>
<tr>
<td width="50%" valign="top">
### 🔬 Sensor Fault Detection
**PyTorch · LSTM-FCN · SMOTE · UCI SECOM**
 
Dual-branch LSTM-FCN on 590-sensor data (93/7 imbalance). Leakage-free pipeline. Failure diagnosed via PCA + t-SNE — dataset-level root cause, not modeling.
 
`Macro F1: 0.55 · 266K params`
 
[![GitHub](https://img.shields.io/badge/GitHub-sensor--fault--detection-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/sensor-fault-detection)
 
</td>
<td width="50%" valign="top">
### 🌫️ Air Quality Forecasting
**PyTorch · FastAPI · Streamlit · Time-Series**
 
Hourly NO₂ from 72-step multivariate stream. Full pipeline: imputation → normalization → LSTM → API → UI.
 
`MAE 46.65 μg/m³ · ~35% vs persistence`
 
[![Demo](https://img.shields.io/badge/Demo-Streamlit-FF4B4B?style=flat-square)](https://air-quality-prediction-ehb9tnezgfquw42hvveumr.streamlit.app)
[![GitHub](https://img.shields.io/badge/GitHub-air--quality--prediction-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/air-quality-prediction)
 
</td>
</tr>
<tr>
<td width="50%" valign="top">
### 🎙️ LLM Voice Assistant
**STT → LLM → TTS · Wake Word · 14 modules**
 
Dual-backend LLM (OpenAI + HuggingFace), real-time STT, neural TTS, wake-word detection. Hot-swap provider with no code change.
 
[![Demo](https://img.shields.io/badge/Demo-HuggingFace-yellow?style=flat-square)](https://hasanbahceci-voice-assistant.hf.space)
[![GitHub](https://img.shields.io/badge/GitHub-voice__assistant-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/voice_assistant)
 
</td>
<td width="50%" valign="top">
### 🐾 Cat vs Dog Classifier
**TensorFlow · MobileNetV2 · ONNX Runtime**
 
2-phase transfer learning (frozen extraction → fine-tune). Exported to ONNX for CPU-efficient inference.
 
`Test Accuracy: 98.70% · ~14ms CPU (ONNX)`
 
[![Demo](https://img.shields.io/badge/Demo-Streamlit-FF4B4B?style=flat-square)](https://hasanbahcecii-cat-dog-image-classifier-app-gtgtuq.streamlit.app)
[![GitHub](https://img.shields.io/badge/GitHub-cat--dog--classifier-black?style=flat-square&logo=github)](https://github.com/hasanbahcecii/cat-dog-image-classifier-cnn)
 
</td>
</tr>
</table>
---
 
## 🛠️ Tech Stack
 
**Robotics & Embedded**
 
![ROS2](https://img.shields.io/badge/ROS2_Humble-22314E?style=flat-square&logo=ros&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
 
`NVIDIA Jetson TX2 · CAN bus · GigE Vision · STM32 · AVR/ATmega328P · Arduino · Verilog · TensorRT · Docker`
 
**AI / ML**
 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
 
`CNN · LSTM · GRU · TCN · GNN · Transformer · UKF · Transfer Learning · Time-Series · Computer Vision`
 
**Deployment & Tools**
 
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
 
`REST APIs · OpenAI API · Hugging Face · ONNX Runtime`
 
**Mobile**
 
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
 
`Dart`
 
---
 
## 🎓 Education
 
| | |
|---|---|
| **Erzurum Technical University** | B.Sc. Computer Engineering (English) · 2022–2027 |
| **Politechnika Lubelska** | Erasmus+ Exchange · GPA 3.74/4.0 · Oct 2024 – Feb 2025 |
 
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=80&section=footer" width="100%"/>
</div>
 
