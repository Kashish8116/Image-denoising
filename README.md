
# Zero-DCE for Low-Light Image Enhancement




## Overview
Zero-DCE is a deep learning-based method designed to enhance low-light images by estimating an illumination map and performing curve adjustment. This project implements the Zero-DCE technique to significantly improve the visual quality of images captured under low-light conditions.

## Features
Deep Learning Model: Utilizes a deep neural network to train the LOL dataset for illumination estimation and enhancement.

Enhancement Techniques: Applies curve adjustment to improve brightness and overall image quality.

Python Implementation: Implemented in Python(Jupyter Notebook) using TensorFlow/Keras for deep learning and image processing.
## Installation Prerequisites
Python 3.x
TensorFlow 2.x (or TensorFlow 1.x with Keras)
NumPy
OpenCV (optional, for image I/O)

Install dependencies using pip:
pip install tensorflow numpy opencv-python
## Running the Enhancement Process
Prepare Input Images:

Place your low-light images in a directory (input_images/ for example) within the project folder.

Run the Enhancement Script:
Training code
## Model Details 
The Zero-DCE model used in this project is based on https://in.docworkspace.com/d/sIKf3qL1K7orHswY?sa=cl.

Contributions are welcome! If you have suggestions or improvements, please fork the repository and create a pull request. For major changes, please open an issue first to discuss what you would like to change.
## License

This project is licensed under the MIT License - see the LICENSE file for details.
## Acknowledgments
The Zero-DCE method was proposed in https://arxiv.org/abs/2001.06826.