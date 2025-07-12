✍️ Handwritten Text Recognition System
Personal Project | June 2023 – Dec 2023

A machine learning and computer vision system that transcribes handwritten text images into digital text. Built upon the robust SimpleHTR TensorFlow pipeline, with personalized improvements to enhance accuracy, usability, and real-world integration.

🚀 Project Overview
Objective: Convert images of handwritten text—words or full lines—into digital text with high accuracy.

Base System: Uses CNN + RNN (CTC) architecture from githubharald’s SimpleHTR 
Reddit
+12
GitHub
+12
githubharald.github.io
+12
Gitee
.

Personal Enhancements:

Integrated data augmentation for handwriting variability (contrast, rotations).

Implemented confidence scoring and threshold-led filtering for reliable transcription.

Added modular input handling for word vs. line mode (128×32 input size) .

Designed example scripts for batch processing and real-time inference.

📁 Repository Structure
bash
Copy
Edit
.
├── data/                  # Preprocessed training/test word & line images
├── model/                 # Pre-trained model weights (SimpleHTR format)
├── src/
│   ├── main.py            # Custom entry script: train/infer/batch modes
│   ├── config.py          # Configurable paths, thresholds, and modes
│   ├── augment.py         # Data augmentation module
│   └── utils.py           # Preprocessing, confidence scoring, loading
├── requirements.txt
└── README.md
