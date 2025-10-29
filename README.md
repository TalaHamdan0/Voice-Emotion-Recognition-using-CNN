# Voice-Emotion-Recognition-using-CNN


### Project Description
This project is a **Voice Emotion Recognition system** that classifies emotions from speech audio files.  
It uses **MFCC feature extraction** and a **Convolutional Neural Network (CNN)** for multi-class emotion classification.

### Emotions Classified
- Neutral
- Calm
- Happy
- Sad
- Angry
- Fearful
- Disgust
- Surprised

### Features
- Extracts **MFCCs** from audio files and pads/truncates them for CNN input.
- Builds a **CNN model** with Conv2D, MaxPooling, Dropout, and Dense layers.
- Trains on the **RAVDESS dataset** (or similar voice datasets).
- Evaluates with **accuracy and classification report**.

### Tools & Libraries
- Python
- Librosa
- NumPy
- TensorFlow/Keras
- scikit-learn
- Jupyter Notebook

### How to Run
1. Clone the repository.  
2. Install required libraries:  
```bash
pip install numpy librosa tensorflow scikit-learn

---

