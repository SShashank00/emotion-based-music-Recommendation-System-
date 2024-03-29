# Emotion-Based Music Recommender WebApp

Welcome to our project on emotion-based music recommendation! This project utilizes various technologies including Mediapipe, Keras, OpenCV, and Streamlit to create a web application where users can capture their webcam feed and receive music recommendations based on their detected emotions.

## Overview

In this project, we have developed a web application that leverages computer vision and machine learning techniques to detect facial expressions in real-time using the user's webcam feed. Based on the detected emotions, the application recommends music tracks that correspond to the user's current mood.

## Technologies Used

- **Mediapipe**: Utilized for facial landmark detection and facial expression recognition.
- **Keras**: Employed for training the emotion recognition model.
- **OpenCV**: Used for image processing tasks such as reading webcam feed and displaying the results.
- **Streamlit**: Framework for building interactive web applications with Python.
- **Streamlit-WebRTC**: Module for capturing webcam feed directly within the browser.

## Video Tutorial

To assist with understanding the code and the process of creating the web application, we have provided a detailed video tutorial. You can watch the tutorial [here](link_to_video).

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Run the Streamlit application with `streamlit run app.py`.
4. Open the provided URL in your web browser to access the web application.

## Code Structure

- `app.py`: Main Python script containing the Streamlit application code.
- `model.py`: Script for defining and training the emotion recognition model using Keras.
- `utils.py`: Utility functions for image processing and interfacing with Mediapipe and OpenCV.
- `requirements.txt`: List of Python dependencies required to run the application.

## Contributing

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.
