# ✋ Sign Language Recognition using CNN  

This project implements a **deep learning-based Sign Language Recognition system** using **Convolutional Neural Networks (CNNs)**. The model is trained on a large dataset of gesture images representing **alphabets (A–Z), digits (0–9), and special characters**.  

## 📌 Project Overview  
- 🎯 **Goal:** Build a real-time sign language recognition model to assist communication for speech- and hearing-impaired individuals.  
- 📊 **Dataset:** 55,500 labeled gesture images across **36 classes** (A–Z, 0–9, and “_”).  
- ⚙️ **Frameworks & Tools:** Python, TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Jupyter.  
- 🚀 **Output:** A production-ready model capable of recognizing gestures from images and real-time webcam input.  

---

## 🛠 Features  
- Preprocessing of raw gesture images using **OpenCV augmentation** (rotation, scaling, brightness adjustment).  
- **CNN architecture** with >2M trainable parameters for gesture classification.  
- Achieved **98.7% test accuracy** and **F1-score of 0.984**.  
- Supports **real-time predictions** from camera feed.  
- Built with an interactive **Gradio UI** for testing and deployment.  

---

## 📸 Demo  

Here’s the system in action:  

![Demo Screenshot](Screenshot%202025-09-07%20191843.jpg)  

---

## 🚀 Installation & Usage  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/sign-language-recognition.git
cd sign-language-recognition
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Train the model
```bash
python train.py
```
### 4. Run the demo (Gradio App)
```bash
python app.py
```
## 📂 Project Structure


├── data/                 # Dataset (not included in repo)
├── notebooks/            # Jupyter notebooks for training & experiments
├── models/               # Saved models
├── app.py                # Gradio demo app
├── train.py              # Training script
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
