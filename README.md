Human Activity Recognition Using LSTM+CNN

Overview

This project focuses on recognizing human activities in videos using a hybrid deep learning model that combines LSTM and CNN architectures. The CNN extracts spatial features from video frames, while the LSTM captures temporal dependencies, enabling accurate classification of sequential activities.

Features

Preprocessing: Extracted frames from video data and normalized for consistency.
Model Architecture:
CNN: For spatial feature extraction from individual frames.
LSTM: For learning temporal patterns across sequences.
Dataset: Processed video datasets with labeled activities.
Training: Implemented using TensorFlow/Keras with techniques like early stopping and learning rate scheduling.
Output: Predicted activity classes for input video sequences.
Requirements

Programming Language: Python
Libraries:
TensorFlow/Keras
NumPy, Pandas
OpenCV (for video frame extraction)
Matplotlib/Seaborn (for visualization)
