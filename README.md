# Eyewear Detection using CNN

This project implements a simple Convolutional Neural Network (CNN) model to classify whether a person is wearing glasses or not. The model is integrated into a web application using Flask, allowing users to upload images and receive real-time predictions.

## Features

- Image classification (Glasses vs No Glasses)
- Trained using Keras and TensorFlow
- Flask-based web interface for image upload and prediction
- Modular structure for easy extension and deployment

## Project Structure

eyewear-detection-cnn/
├── app.py                     # Flask backend
├── model.h5                   # Trained CNN model
├── eyewear_model.ipynb        # Jupyter notebook for model training
├── requirements.txt           # Python dependencies
└── templates/
    └── index.html             # HTML interface for image upload

## How to Run the Project

### 1. Clone the Repository

git clone https://github.com/Varunprakash27/eyewear-detection-cnn.git
cd eyewear-detection-cnn

### 2. Create and Activate a Virtual Environment (Optional but Recommended)

python -m venv venv
venv\Scripts\activate    # On Windows
# source venv/bin/activate   # On Linux/Mac

### 3. Install Dependencies

pip install -r requirements.txt

### 4. Run the Flask App

python app.py

The app will start on http://127.0.0.1:5000/. Open it in your browser.

### 5. Upload an Image

Use the web interface to upload an image of a face. The app will return whether the person is wearing glasses or not.

## Model Information

- Input size: 64x64 pixels
- Architecture: Custom CNN with Conv2D, MaxPooling2D, Flatten, Dense
- Output: Binary classification (0 = Glasses, 1 = No Glasses)
- Frameworks: TensorFlow, Keras

## Dependencies

- Flask
- TensorFlow
- Keras
- NumPy

All dependencies are listed in requirements.txt.

## License

This project is open-source and available under the MIT License.

## Author

Varun Prakash  
GitHub: https://github.com/Varunprakash27
