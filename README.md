# 🔊 Deep Audio Classifier with TensorFlow 🎧

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)
![Audio](https://img.shields.io/badge/Audio-Classification-green?style=for-the-badge)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNNs-yellow?style=for-the-badge)

---

### 📌 Project Overview

This project implements a **Deep Learning-based Audio Classifier** using **Python** and **TensorFlow**. It can recognize and classify sounds from raw audio files (WAV/MP3) by converting them into spectrograms and feeding them into a CNN-based model.

🚀 Ideal for:
- Environmental sound classification  
- Voice-based commands  
- Audio anomaly detection  
- Smart assistants & IoT sound triggers

---

### 🎯 Key Features

- 🎵 Supports multiple audio classes (e.g., dog bark, siren, speech)
- 🎛 Converts audio signals to Mel-spectrograms using `Librosa`
- 🧠 Uses a Convolutional Neural Network (CNN) for audio pattern learning
- 📊 Includes training/validation metrics visualization
- 🛠️ Modular and clean code for easy experimentation

##

### 🛠️ Tech Stack

| Component        | Description                             |
|------------------|-----------------------------------------|
| **Language**     | Python 3.10+                             |
| **Libraries**    | TensorFlow, Librosa, NumPy, Matplotlib  |
| **Model**        | CNN for multi-class audio classification|
| **Input**        | WAV/MP3 files                           |
| **Output**       | Predicted class label + confidence score|

##

### 🧪 How It Works

#### 1️⃣ Data Preprocessing

- Load audio files (.wav/.mp3) using `librosa`
- Convert to **Mel Spectrograms**
- Normalize and reshape for CNN input

#### 2️⃣ Model Architecture

- 3 Conv2D layers with ReLU + MaxPooling
- Flatten → Dense → Softmax
- Compiled with `categorical_crossentropy` + Adam

#### 3️⃣ Training & Evaluation

- Model trained on labeled audio dataset
- Accuracy & loss tracked on train/val sets
- Final model saved in `.h5` format


##

### 📈 Future Enhancements

- 🎙️ Add real-time microphone input support
- 🧠 Integrate transfer learning with VGGish / YAMNet
- 🌐 Deploy as a web app (Streamlit or FastAPI)
- 📦 Export model for mobile or edge devices (TFLite)


##

### 📫 Connect with Me

- LinkedIn: [Hariharan Balasubramanian](https://www.linkedin.com/in/hariharan-balasubramanian97)
- Email: hariharanbalasubramanian4@gmail.com

---

### ⭐ If You Like This Project
If this project helped or inspired you, please ⭐ star the repo and share it!

---

### 🙏 Thank You...!!!

