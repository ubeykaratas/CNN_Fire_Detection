# Fire Detection Model

This is a **fire detection model** using **Convolutional Neural Networks (CNN)**. The application allows users to upload images and classify whether there is a fire in the image or not.

## Project Overview

- **Fire Detection Model**: A CNN-based deep learning model trained to detect fire in images.
- **Web Interface**: A Django web application where users can upload images for fire detection.
- **Performance Metrics**: Includes graphs showing the model's accuracy, loss, and other performance metrics during training.

## Features

- Upload an image to check if it contains fire.
- Real-time prediction and result display.
- Easy-to-use interface built with Django.

## Technologies Used

- **PyTorch**: For building and training the CNN model.
- **Django**: Web framework for the user interface.
- **Python**: Programming language used for the project.
- **OpenCV/PIL**: For image preprocessing.
- **Matplotlib/Seaborn**: For visualizing training results and performance metrics.
- **scikit-learn**: For computing evaluation metrics (accuracy, F1-score, etc.).

## Installation

Navigate to the **"image_classifier/"** directory and run the Django development server:
   ```bash
   python manage.py runserver
