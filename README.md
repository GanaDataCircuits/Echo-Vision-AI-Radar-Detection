# Echo-Vision-AI-Radar-Detection
AI-powered radar-based human detection system using spectrogram analysis and CNN, with real-time visualization via Streamlit.

## 📌 Overview
EchoVision is an AI-powered system designed to detect human presence behind obstacles using radar signal processing and deep learning techniques. The project simulates radar signals, converts them into spectrograms, and applies a Convolutional Neural Network (CNN) for classification.

## 🚀 Key Features
- 📡 Radar signal simulation (human vs non-human)
- 📊 Spectrogram generation for feature extraction
- 🧠 CNN-based deep learning model for classification
- 🌐 Interactive Streamlit web application for real-time detection
- 📈 Visualization of model performance and signal patterns

## 🧠 Methodology
1. Simulated radar signals representing human motion and background noise  
2. Converted signals into spectrograms using signal processing techniques  
3. Trained a CNN model on spectrogram images  
4. Evaluated model performance using accuracy and classification metrics  
5. Deployed the model using Streamlit for real-time interaction  

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, SciPy  
- Matplotlib  
- Streamlit  

## 📊 Results
- Achieved high classification accuracy in detecting human presence  
- Clear distinction between structured (human) and noisy (non-human) spectrograms  
- Real-time prediction capability through web interface  

## ▶️ How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
