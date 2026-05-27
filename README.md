# AI & Machine Learning Projects Portfolio

This repository contains three machine learning and AI-based projects developed using Python, TensorFlow, Streamlit, and Stable Diffusion. These projects demonstrate practical implementations of Deep Learning, Computer Vision, Generative AI, and Data Analysis concepts.

# Project 1 – Image Colorization using CNN
Problem Statement – Project 1
Image Colorization using CNN

Many historical and grayscale images lack visual information, making them less engaging and harder to interpret. Manual image colorization is time-consuming and requires artistic expertise. The challenge is to automatically generate realistic colorized images from grayscale inputs while preserving image quality and structural details.

This project aims to solve this problem using a Convolutional Neural Network (CNN) that learns color patterns from images and predicts appropriate color channels for grayscale images using the LAB color space.
## 📖 Overview

This project focuses on automatic image colorization using a Convolutional Neural Network (CNN).
The model takes grayscale images as input and predicts realistic colorized versions using the LAB color space.

The project uses:

* TensorFlow/Keras
* OpenCV
* scikit-image
* NumPy
* Matplotlib


## Objective

To convert grayscale images into colorized images using Deep Learning techniques.


## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* scikit-image

## Model Architecture

The CNN model consists of:

* Encoder layers for feature extraction
* MaxPooling layers for dimensionality reduction
* Decoder layers with UpSampling
* Final output layer predicting A & B color channels

The model is trained using:

* Mean Squared Error (MSE) Loss
* Adam Optimizer


## Dataset

Images used:

* nature.jpg
* nature_3.jpg
* nature_4.jpg

Images are:

* Resized to 256×256
* Converted from RGB to LAB color space
* L channel used as input
* AB channels used as target output

## Evaluation

The model performance is evaluated using:

* Structural Similarity Index (SSIM)

## Features

* Automatic grayscale image colorization
* LAB color space processing
* CNN-based encoder-decoder architecture
* Image visualization and saving
* SSIM score calculation

# Project 2 – AI Image Generator using Stable Diffusion
Problem Statement – Project 2
AI Image Generator using Stable Diffusion

Creating high-quality digital artwork often requires advanced design skills, expensive software, and significant time investment. With the rise of Generative AI, there is a growing need for accessible tools that allow users to generate creative and visually appealing images using simple text prompts.

This project aims to develop an AI-powered image generation application using Stable Diffusion that enables users to create unique artworks in multiple styles through an interactive Streamlit interface.
## Overview

This project is a Streamlit-based AI Image Generator powered by Stable Diffusion.
Users can generate creative AI images from text prompts with different artistic styles.


## Objective

To build an interactive Generative AI application capable of producing high-quality AI-generated artwork from text prompts.


## Technologies Used

* Python
* Streamlit
* Hugging Face Diffusers
* Stable Diffusion
* PyTorch
* Ngrok

## Features

* AI image generation from prompts
* Multiple art styles
* Surprise prompt generator
* Fast Mode & Quality Mode
* Recent image gallery
* Image download support
* Public deployment using Ngrok

## Model Used

* Stable Diffusion v1.4
* Hugging Face Diffusers Pipeline

## Functionalities

### Prompt Styling

Enhances prompts with artistic effects.

### Style Selection

Available styles include:

* Hyper-realistic
* Anime Style
* Digital Painting
* Cyberpunk
* 3D Render

### Prompt History

Stores previously generated prompts.

### Gallery Section

Displays recently generated AI images.


# Project 3 – Mental Health Dataset Analysis
Problem Statement – Project 3
Mental Health Dataset Analysis

Mental health issues are becoming increasingly common, but identifying patterns and factors influencing mental well-being can be challenging due to large and complex datasets. Organizations and researchers need efficient ways to analyze mental health-related data to better understand stress levels, treatment patterns, and behavioral trends.

This project aims to perform exploratory data analysis (EDA) on a large mental health survey dataset to uncover meaningful insights, identify trends, and support data-driven understanding of mental health conditions and related factors.
## Overview

This project performs exploratory data analysis (EDA) on a Mental Health Dataset containing survey responses related to stress, treatment, habits, and mental health conditions.

The analysis helps understand patterns and trends affecting mental health.

## Objective

To analyze mental health-related data and identify trends using Python data analysis libraries.


## Technologies Used

* Python
* Pandas
* NumPy


## Dataset Information

Dataset contains:

* 292,364 rows
* 17 columns

Features include:

* Gender
* Country
* Occupation
* Family History
* Treatment
* Stress Levels
* Mood Swings
* Social Weakness
* Work Interest
* Mental Health Interview

## Data Preprocessing

Performed:

* Null value detection
* Missing value handling
* Data cleaning
* Column inspection
* Statistical summary generation

## Analysis Performed

* Dataset shape inspection
* Null value analysis
* Feature exploration
* Category analysis
* Descriptive statistics
* Data cleaning and preprocessing


# Repository Structure

```bash
├── Image_Colorization_Project/
├── AI_Image_Generator/
├── Mental_Health_EDA/
├── README.md
```


# Future Improvements

## Image Colorization

* Train on larger datasets
* Add GAN-based colorization
* Improve output quality

## AI Image Generator

* Add image-to-image generation
* Add user authentication
* Deploy on cloud platforms

## Mental Health Analysis

* Add visualizations
* Build prediction models
* Create dashboards using Streamlit

# Conclusion

These projects demonstrate practical applications of:

* Deep Learning
* Computer Vision
* Generative AI
* Data Analysis
* Streamlit Web Applications

They helped strengthen understanding of:

* CNN architectures
* Stable Diffusion pipelines
* Dataset preprocessing
* Model evaluation techniques
* AI application deployment


# Author

Dharshini Rajasekaran

MSc Data Analytics Student
passionate about AI, Machine Learning, and Data Science
