# CNN-Based Grayscale Image Colorization using Stable Diffusion

## Project Overview
This project focuses on automatic colorization of grayscale images using Convolutional Neural Networks (CNN) integrated with Stable Diffusion techniques. The main objective of the project is to transform black-and-white images into realistic and visually appealing colored images using deep learning models.

Image colorization is one of the important applications of Artificial Intelligence and Computer Vision. Manual colorization requires professional editing skills and consumes a lot of time. This project aims to automate the process by training deep learning models to predict accurate color information from grayscale images.

The model learns image features, textures, edges, and patterns from large datasets and generates realistic colors while preserving the original structure of the image.



## Objectives
- Convert grayscale images into realistic colored images
- Improve image quality using deep learning techniques
- Learn feature extraction using CNN architectures
- Generate visually accurate color predictions
- Explore Stable Diffusion techniques for enhanced image generation

-
## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Google Colab
- Stable Diffusion
- CNN (Convolutional Neural Networks)


## Dataset Used
The project uses grayscale and colorful image pairs for training the model.

Dataset:
- Image Colorization Dataset by aayush9753 from Kaggle

The dataset contains:
- Original colorful images
- Corresponding grayscale images

These image pairs help the model learn color mapping and prediction.


## Methodology

### 1. Data Preprocessing
- Images are resized and normalized
- Conversion between RGB and LAB color spaces
- Extraction of L (Lightness) channel for grayscale input
- AB color channels used as target output

### 2. CNN Model Architecture
The Convolutional Neural Network is designed to:
- Extract image features
- Detect patterns and textures
- Predict missing color channels
- Generate realistic color outputs

The network includes:
- Convolution layers
- Activation functions
- Pooling layers
- Upsampling layers

### 3. Stable Diffusion Integration
Stable Diffusion techniques are used to improve:
- Image quality
- Color smoothness
- Realistic appearance
- Fine image details

This helps generate visually enhanced and natural-looking colored images.

### 4. Model Training
The model is trained on grayscale-color image pairs using:
- Loss optimization
- Backpropagation
- Epoch-based learning

The model gradually improves its color prediction accuracy during training.

---

## Features
- Automatic grayscale image colorization
- Deep learning-based image processing
- Realistic color prediction
- Enhanced output quality using Stable Diffusion
- Visualization of input and output images
- Image preprocessing and normalization


## Results
The trained model successfully generates colored versions of grayscale images with visually realistic outputs. The project demonstrates the capability of CNNs and Stable Diffusion techniques in solving image restoration and enhancement problems.

The generated outputs preserve:
- Image structure
- Object boundaries
- Texture details
- Natural color appearance



## Applications
- Restoration of old black-and-white photographs
- Film and media restoration
- Historical image enhancement
- AI-based image editing
- Computer vision research



## Future Enhancements
- Improve color accuracy using larger datasets
- Use GAN-based architectures
- Deploy as a web application
- Real-time image colorization
- Higher resolution image generation


## Learning Outcomes
Through this project, I learned:
- Deep learning fundamentals
- CNN architecture design
- Image preprocessing techniques
- Computer vision concepts
- Stable Diffusion integration
- Model training and evaluation
- TensorFlow and OpenCV implementation

---

## Author
Dharshini Rajasekaran

GitHub: https://github.com/Dharshini-git969
