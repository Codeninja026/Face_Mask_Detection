# 😷 Face Mask Detection using VGG16 and OpenCV

This project is a deep learning application that detects whether a person is wearing a face mask or not in real-time using their webcam. It uses the **VGG16 CNN model** for feature extraction and classification, combined with **OpenCV** for live video feed processing.

---

## Features
- Real-time face mask detection using your webcam.
- Uses pre-trained **VGG16** for high-accuracy image classification.
- Live face detection and recognition using **OpenCV**.
- Efficient and lightweight — works on most computers with a webcam.

---

## Model
- Base Model: `VGG16` from Keras (pre-trained on ImageNet)
- Fine-tuned on face mask datasets with two classes:
  - `Mask`
  - `No Mask`

---

## Tech Stack
- Python
- OpenCV (`cv2`)
- TensorFlow / Keras (VGG16)
- NumPy
- Matplotlib (for visualizations)
