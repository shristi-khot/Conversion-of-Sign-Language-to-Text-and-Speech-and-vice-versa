# Conversion-of-Sign-Language-to-Text-and-Speech-and-vice-versa

This project focuses on enhancing communication between hearing-impaired individuals and others by enabling real-time translation between sign language, text, and speech. It involves detecting hand gestures and converting them into readable and audible formats — and vice versa.

## 🧩 Features

- 🎯 **Sign Language to Text Conversion**  
  Real-time hand gesture recognition using computer vision and machine learning models.

- 🔊 **Sign Language to Speech**  
  Converts detected sign gestures into audible speech using a text-to-speech engine.

- 🎤 **Speech/Text to Sign Language**  
  Converts spoken words into animated sign language representations.

🛠️ Tech Stack
🧑‍💻 Programming Language
Python: Primary language used for model development, hand tracking, gesture recognition, NLP processing, and TTS integration.

🧠 Deep Learning Frameworks
TensorFlow: For designing, training, and deploying Convolutional Neural Networks (CNNs) used in gesture recognition.

Keras: A high-level API running on top of TensorFlow to simplify neural network design and experimentation.

🔓 Open Source Framework
MediaPipe: Used for real-time detection and tracking of hand landmarks, offering highly accurate keypoint extraction.

👁️‍🗨️ Computer Vision Libraries
OpenCV: Employed for image/video frame processing, gesture tracking, region of interest (ROI) detection, and visualization.

🗣️ Natural Language Processing & Speech Tools
NLTK (Natural Language Toolkit): For converting recognized gesture outputs into grammatically correct and structured sentences.

Text-to-Speech (TTS) APIs: Google Text-to-Speech (gTTS)

## 🧠 Methodology

1. **Sign Detection**:  
   Hand gestures are captured using a webcam and processed using MediaPipe or OpenCV to extract hand landmarks.

2. **Gesture Classification**:  
   A trained ML or DL model predicts the gesture based on landmark coordinates or image frames.

3. **Text & Speech Conversion**:  
   - For output: The recognized gesture is converted to text and passed to a text-to-speech engine.
   - For input: Spoken words are translated into corresponding sign gestures using animations.
