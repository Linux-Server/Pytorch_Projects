# Facial Expression Recognition

This project implements a facial expression recognition system using PyTorch, based on the Coursera course "Facial Expression Recognition with PyTorch".

## Project Overview
The system is designed to detect and classify human facial expressions into different emotion categories. This project is part of the Coursera course curriculum and implements a CNN-based approach for facial expression recognition.

## Environment
- Python 3.11
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Other dependencies will be listed in requirements.txt

## Project Structure
```
facial_expression_recognition/
├── data/           # Dataset directory
│   └── fer2013/    # FER2013 dataset
├── models/         # Model architecture definitions
│   └── cnn.py      # CNN model implementation
├── utils/          # Utility functions
│   ├── data_loader.py    # Dataset loading utilities
│   └── visualization.py  # Visualization tools
├── train.py        # Training script
├── predict.py      # Prediction script
└── requirements.txt # Project dependencies
```

## Dataset
The project uses the FER2013 dataset, which contains 35,887 grayscale images of faces with 7 emotion categories:
- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

## Usage
1. Download the FER2013 dataset
2. Install dependencies: `pip install -r requirements.txt`
3. Train the model: `python train.py`
4. Make predictions: `python predict.py`

## License
This project is part of the Coursera course "Facial Expression Recognition with PyTorch". Please refer to Coursera's terms of service and the course materials for licensing information. 