# Facemask Detection

## Overview
This repository contains a deep learning-based facemask detection system that can identify whether a person is wearing a mask, not wearing a mask, or wearing a mask improperly. The project utilises computer vision techniques and convolutional neural networks (CNNs) to achieve real-time detection.

## Features
- Detects faces with and without masks.
- Identifies improperly worn masks.
- Utilises pre-trained deep learning models for efficient detection.
- Can be integrated with real-time video streams.

## Installation
### Prerequisites
Ensure you have the following dependencies installed:
- Python 3.x
- OpenCV
- TensorFlow/Keras
- NumPy
- Matplotlib

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Arpeeet/Facemask-Detection.git
   cd Facemask-Detection
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download pre-trained models (if applicable) and place them in the specified directory.

## Usage
Run the detection script:
```bash
python detect_mask.py
```
For real-time detection using a webcam:
```bash
python detect_mask_video.py
```

## Dataset
The model is trained using a dataset containing images of people with and without masks. It has been pre-processed and augmented to improve detection accuracy.

## Model Architecture
- Utilises a CNN-based architecture.
- Pre-trained models such as MobileNetV2 may be used for feature extraction.
- Custom classification layers for mask detection.

## Results
The model achieves high accuracy on test datasets and performs well in real-world scenarios.

## Contribution
Feel free to contribute by submitting pull requests or reporting issues.

## License
This project is licensed under the MIT License.

## Acknowledgements
- Open-source datasets for facemask detection.
- Deep learning frameworks such as TensorFlow and Keras.
- Community contributions for real-time applications.

