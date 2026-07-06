# Chest X-ray Image Enhancement and Classification Using Convolution, Machine Learning, and Deep Learning in Python

## Overview

This project presents a Python-based framework for enhancing and classifying chest X-ray images using image processing, machine learning, and deep learning concepts. The system improves image quality through Gaussian filtering, performs edge detection using convolution, extracts statistical features, and classifies images using a logistic regression model implemented from scratch with NumPy.

---

## Features

- Chest X-ray image preprocessing
- Gaussian filtering for noise removal
- Manual and optimized convolution for edge detection
- Statistical feature extraction
- Feature normalization
- Logistic regression classifier using NumPy
- Loss and accuracy visualization
- Execution time comparison of convolution methods

---

## Technologies Used

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

---

## Project Structure

```
Chest-Xray-Classification/
│
├── dataset/                  # Chest X-ray images
├── main.py                   # Main source code
├── README.md                 # Project documentation
└── output/                   # Generated results
```

---

## Methodology

1. Load chest X-ray images from the dataset.
2. Resize images to a standard resolution.
3. Remove noise using Gaussian filtering.
4. Apply convolution for edge detection.
5. Extract statistical image features.
6. Normalize extracted features.
7. Train a logistic regression classifier.
8. Evaluate the model using loss and accuracy metrics.
9. Display processed images and training graphs.

---

## Results

The project successfully:

- Reduced image noise using Gaussian filtering.
- Enhanced image edges using convolution.
- Compared manual and optimized convolution performance.
- Extracted meaningful image features.
- Classified chest X-ray images using logistic regression.
- Generated loss and accuracy curves for model evaluation.

---

## Future Scope

- Train using real annotated chest X-ray datasets.
- Implement Convolutional Neural Networks (CNNs).
- Improve classification accuracy using transfer learning.
- Develop a web-based medical diagnosis application.
- Support multi-class disease classification.

---

## Applications

- Medical image analysis
- Computer-aided diagnosis
- Healthcare decision support
- Artificial Intelligence in healthcare
- Academic research and learning

---



---

## License

This project is developed for educational and academic purposes.
