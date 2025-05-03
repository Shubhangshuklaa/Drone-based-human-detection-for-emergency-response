# Drone-based Human Detection for Emergency Response 🚁🔥

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1q4p0cTBYf4RSw2oY6zCZoEJsqqXUjArD?usp=sharing)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Gradio-FF4B4B?logo=gradio)](https://4994f5f5754f2adb67.gradio.live)

---

## 🌟 Overview

**Drone-based Human Detection for Emergency Response** is an AI-powered solution for rapid, accurate detection of human presence in thermal drone imagery. Built for mountain rescue and emergency response teams, it combines deep learning autoencoders with thermal-specific image analysis to highlight potential anomalies (such as lost persons) in challenging environments.

---

## 🚀 Key Features

- 🚨 Real-time anomaly detection from thermal drone images
- 🔥 Thermal-specific bright area analysis for robust human identification
- 📊 Interactive heatmap visualization for easy interpretation
- 🖱️ User-friendly Gradio web interface – no coding required!
- ⚡ Optimized for emergency response and humanitarian use cases

---

## 🧪 Live Testing

👉 **[Test the Live App](https://4994f5f5754f2adb67.gradio.live)**  
Upload your thermal drone images and see instant detection results!

---

## 📂 Dataset

- [Download Thermal Drone Dataset (Google Drive)](https://drive.google.com/drive/folders/1V6qOwVNxbWbTJk8s5H6BNRHh2U1hsxuQ)
- **Contents:**
  - 166 normal training images
  - 60 test images (30 normal / 30 abnormal)
  - Collected with DJI Matrice 300 + Zenmuse H20T
  - 80m altitude, 11°C ambient temperature
- Provided by Black Forest Mountain Rescue Team for humanitarian AI research.

---

## ⚙️ Tech Stack

- **Deep Learning:** TensorFlow/Keras Autoencoder
- **Computer Vision:** OpenCV
- **Interface:** Gradio
- **Training:** Google Colab Pro
- **Visualization:** Matplotlib

---

## ⚡ Quick Start

### 1. Try on Google Colab

[Open the Colab Notebook](https://colab.research.google.com/drive/1q4p0cTBYf4RSw2oY6zCZoEJsqqXUjArD?usp=sharing)  
- Run all cells to load the model and launch the interface.

### 2. Local Installation

git clone https://github.com/Shubhangshuklaa/Drone-based-human-detection-for-emergency-response.git
cd Drone-based-human-detection-for-emergency-response
pip install -r requirements.txt
python app.py

text

---

## 🏗️ Project Structure

Drone-based-human-detection-for-emergency-response/
├── DroneHumanDetection.ipynb # Main Colab notebook
├── app.py # Gradio app launcher
├── requirements.txt # Dependencies
├── best_autoencoder.h5 # Pre-trained model weights
├── data/ # Sample images
│ ├── train/normal
│ └── test/
│ ├── normal
│ └── abnormal
└── README.md

text

---

## 📊 Performance

| Metric    | Score |
|-----------|-------|
| Accuracy  | 85%   |
| Recall    | 88%   |
| Precision | 83%   |
| Inference | 0.2s/image |

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

MIT License - See [LICENSE](LICENSE) for details

---

## 🙏 Acknowledgments

- Dataset provided by Black Forest Mountain Rescue Team
- Gradio for intuitive UI components
- TensorFlow for deep learning framework

---

**Built with ❤️ for the Global AI Hackathon MIT 2025**  
*Every line of code could save a life.*
