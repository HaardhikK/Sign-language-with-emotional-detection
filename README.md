# Indian Sign Language with Emotion Detection

## Overview
This project combines Indian Sign Language (ISL) interpretation with real-time emotion detection. It utilizes a combination of deep learning models to interpret sign language gestures and recognize emotions on faces simultaneously. The system provides a unique interaction experience by allowing users to select from five different Indian languages for spoken txt2speech output.

## Features
- **Real-time ISL Interpretation**: Utilizes a LSTM-based sign language model to interpret gestures in real-time.
- **Emotion Detection**: Employs a Convolutional Neural Network (CNN) model to detect emotions on faces captured in the video feed.
- **Multilingual Support**: Supports five Indian languages for spoken output, enhancing accessibility.
- **Customizable**: Users can easily customize the system by adding more actions or languages.

## Dependencies
- OpenCV
- NumPy
- Matplotlib
- MediaPipe
- TensorFlow
- gTTS (Google Text-to-Speech)
- IPython Widgets
- Translate

## Usage
1. Run the provided Python script (`main.py`) in your terminal or IDE.
2. The system will start capturing video from your webcam.
3. Perform sign language gestures in front of the camera.
4. Emotions detected on your face will be displayed alongside the interpreted gestures.
5. Select your preferred Indian language for spoken output using the provided interface.
6. The interpreted gestures and detected emotions will be spoken out loud in the selected language.
