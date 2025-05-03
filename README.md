# 🖐️ Hand Gesture Recognition using Python & Kaggle Dataset

This project is a simple Hand Gesture Recognition system built with Python. It uses a Kaggle image dataset to train a model that recognizes hand gestures in real-time using your webcam.

## 🎯 Features

- Real-time gesture recognition via webcam
- Recognizes 5 gestures:
  - ✋ Hello
  - 👍 Thumbs Up
  - 👎 Thumbs Down
  - 👌 OK
  - ✊ Fist
- Model trained using image data from Kaggle
- Camera automatically opens when you run the script
- All logic handled in a single `.py` file

## 🛠️ Tech Stack

- Python 3.x
- OpenCV (`cv2`)
- TensorFlow / Keras (used for model training)
- NumPy
- Kaggle (used to download & access training dataset)

## 📁 Folder Structure

hand-gesture-recognition/
│
├── main.py # Main code file – train model + real-time detection
├── dataset/ # (Optional) Your custom or downloaded Kaggle image dataset
├── README.md # This file
└── model.h5 # (Optional) Trained model file saved after training


pip install opencv-python tensorflow numpy kaggle
