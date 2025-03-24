# Internship Studio Artificial Intelligence Internship

> A face recognition system using Multi-Layer Perceptron (MLP) neural networks.

## Project Overview

This project implements a face recognition system using MLP classifier along with Principal Component Analysis (PCA) and Linear Discriminant Analysis (LDA) for dimensionality reduction. The system can identify faces from a dataset of Bollywood celebrities with good accuracy.

## Key Features

- Face detection and recognition using MLP neural network
- Dimensionality reduction using PCA and LDA
- Dataset of Bollywood celebrity faces
- Interactive visualization of eigenfaces
- Model training with loss tracking
- Prediction probability scores
- Accuracy evaluation

## Technical Details

### Technologies Used

- Python
- Jupyter Notebook
- Libraries:
  - scikit-learn (MLPClassifier, PCA, LDA)
  - OpenCV (cv2)
  - NumPy
  - Matplotlib

### Model Architecture

- MLP Neural Network with:
  - Input layer: 150 PCA components
  - Hidden layers: (10, 10) neurons
  - Output layer: Number of classes
  - Maximum iterations: 1000

### Dataset Structure

```
faces/
├── Aamir/
├── Ajay/
├── Akshay/
├── Alia/
├── Amitabh/
├── Deepika/
├── Disha/
├── Farhan/
└── Ileana/
```

### Performance

- Achieved accuracy: ~77.88%
- Model convergence with decreasing loss values
- Early stopping when loss improvement < 0.0001

## How to Run

1. Clone the repository
2. Install required dependencies:
```bash
pip install numpy opencv-python scikit-learn matplotlib jupyter
```
3. Open MLP_Face_Recognition.ipynb in Jupyter Notebook
4. Run all cells sequentially

## Project Structure

```
.
├── faces/                  # Dataset directory
├── MLP_Face_Recognition.ipynb  # Main notebook
└── README.md              # Project documentation
```

## Results

- Successful face recognition with probability scores
- Visualization of eigenfaces
- Loss tracking during training
- Test set predictions with confidence scores

## Author

Chhagan Ram Choudhary
