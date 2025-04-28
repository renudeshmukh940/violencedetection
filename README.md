#Real-Time Violence Detection

A deep learning-based system for detecting violent behavior in real-time video feeds, designed for smart surveillance and public safety. This project uses OpenCV for video processing, TensorFlow for neural network modeling, and Flask for a web-based interface to stream and display violence detection results.

Project Overview

This project detects violent behavior (e.g., fights, aggressive actions) in real-time video streams by processing frames and classifying them as "violent" or "non-violent." It leverages OpenCV for video frame extraction and preprocessing, TensorFlow for a deep learning model (e.g., CNN+LSTM), and Flask to provide a web interface for live streaming and detection results.

The system is optimized for real-time performance and can be integrated into surveillance systems. A custom module (fun.invisibleMinds) handles additional preprocessing or inference logic (update with specifics if applicable, e.g., model loading or feature extraction).


'Technologies Used'





Python 3.8+: Core programming language.



OpenCV (cv2): For video capture, frame processing, and computer vision tasks.



TensorFlow: For building and deploying the deep learning model.



Flask: For creating a web server and streaming detection results.



NumPy: For numerical computations and array operations.



scikit-image (skimage): For image resizing and preprocessing.



fun.invisibleMinds: Custom module for model inference or preprocessing (update with details if public).
