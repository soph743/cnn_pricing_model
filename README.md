# 🏠 Rental Price Predictor Web App
A convolutional neural network (CNN)-powered web application that predicts the rental price range of a property based on uploaded images.

This project is designed to assist renters, landlords, and property analysts by offering quick, image-based rental price estimates using deep learning.

# 🚧 Project Status
Currently in development — final model training and front-end integration are in progress. Codebase and demo will be available soon.

# 🔍 Overview
The app allows users to upload 5 or more images of a rental property (interior, exterior, etc.), and it returns a predicted price range (e.g., $1,500–$2,000/month).

It combines a trained CNN model with a lightweight Flask interface for an accessible, browser-based experience.

# ⚙️ Features
Upload interface for multiple property images

Backend CNN model classifies images into predefined rental price ranges

Lightweight and responsive Flask-based web interface

Clean, intuitive output for non-technical users

# 🧠 Machine Learning Stack
Python

NumPy, Pandas — data manipulation and preprocessing

Scikit-learn — utility functions and evaluation

Keras — deep learning framework for building the CNN

# 🌐 Frontend Stack
Flask — simple, Pythonic web framework for serving the model and handling uploads

# 🗂️ Project Structure (Planned)

```
rental-price-predictor/
│
├── app/                    # Flask app files
│   ├── static/             # CSS/JS/assets
│   ├── templates/          # HTML templates
│   └── app.py              # Main Flask server
│
├── model/                  # Model training + saved weights
│   └── cnn_model.h5
│
├── data/                   # Dataset or processed image data
│
├── requirements.txt        # Required Python packages
└── README.md               # Project documentation
```

# 📌 Goals
Build a robust CNN for real-estate image classification

Ensure model generalizes across diverse property types

Create a fast and accessible prediction workflow through the browser

# 📈 Next Steps
- Finalize dataset preprocessing pipeline

- Train and evaluate CNN on rental price-labeled image dataset

- Implement full Flask integration

- Add user authentication and session tracking (optional)

# 📬 Contact
For questions or collaboration inquiries:
Sophia Cherkaoui
📧 [sophia.cherkaoui001@umb.edu]


external links

https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator

https://datascience.stackexchange.com/questions/48390/how-do-i-build-an-image-dataset-for-cnn
