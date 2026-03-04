# Final Project: Emotion Detector using Watson NLP

This repository contains the **Final Project** for the IBM course  
**"Developing AI Applications with Python and Flask"**.

The project implements an AI-powered **Emotion Detection web application** using the Watson NLP library. The application analyzes user-provided text and identifies emotions such as anger, disgust, fear, joy, and sadness. It also determines the dominant emotion in the analyzed text.

---

## Project Overview

The application performs the following steps:

1. Accepts user input through a web interface.
2. Sends the text to the Watson NLP Emotion Detection API.
3. Processes the response returned by the API.
4. Displays the emotion scores and the dominant emotion.

The project demonstrates how AI services can be integrated into a web application using Python and Flask.

---

## Technologies Used

- Python
- Flask
- Watson NLP Emotion Detection API
- HTML / CSS
- Unit Testing
- Static Code Analysis (pylint)

---

## Project Structure
emotion-detection-final-project/
│
├── EmotionDetection/
│ ├── init.py
│ └── emotion_detection.py
│
├── templates/
│ └── index.html
│
├── static/
│
├── server.py
├── test_emotion_detection.py
└── README.md

---

## Running the Application

To start the Flask server, run:

Then open the application in your browser.

---

## Example Input
I love this technology

Example Output:
For the given statement, the system response is
'anger': 0.013241, 'disgust': 0.002052, 'fear': 0.009091,
'joy': 0.969952, 'sadness': 0.054984.
The dominant emotion is joy.

---

## Features

- Emotion analysis using Watson NLP
- Flask web interface
- Error handling for invalid input
- Unit tests for application validation
- Static code analysis using pylint

---

## Author

David Barone

