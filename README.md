# AI Emotion Detection Web Application

This project implements an AI-powered emotion detection system using Natural Language Processing (NLP).

The application analyzes user input text and predicts emotional states based on probability scores. The system identifies five emotions:

- anger
- disgust
- fear
- joy
- sadness

The dominant emotion is automatically determined based on the highest probability score.

---

# Project Overview

This application provides a simple web interface where users can enter text and receive an emotional analysis.

The backend processes the text and sends it to the IBM Watson NLP Emotion Prediction API. The API returns probability scores for each emotion, which are then displayed in the browser.

---

# Architecture

The application consists of three main components.

## Backend (Python / Flask)

Handles:

- HTTP requests
- API communication
- emotion prediction processing
- returning the results to the frontend

Main backend file:


Emotion detection logic:

---

## Frontend (HTML / JavaScript)

User interface for entering text and displaying results.

---

## Frontend (HTML / JavaScript)

User interface for entering text and displaying results.

---

## NLP Emotion API

The application uses the IBM Watson NLP Emotion Prediction model.

The API returns probability scores for:

- anger
- disgust
- fear
- joy
- sadness

---

# Application Flow

1. User enters text in the web interface
2. JavaScript sends the text to the Flask backend
3. Flask calls the Watson NLP Emotion Prediction API
4. API returns emotion probabilities
5. The system determines the dominant emotion
6. Results are displayed in the browser

---

# Example

Input text

Output

Dominant emotion

---

# Technology Stack

- Python
- Flask
- IBM Watson NLP API
- HTML
- JavaScript
- REST API integration

---

# Installation

Clone the repository:


Install dependencies:

Run the application:

Open in your browser:

---

# Learning Objective

This project was created as part of the **IBM / Coursera NLP Emotion Detection Final Project**.

The objective was to build a working NLP application that:

- integrates an external AI model
- processes text data
- returns structured emotion predictions
- provides a web-based interface

---

# Author

David Barone

Digital Transformation | AI Strategy | Python | NLP

GitHub  
https://github.com/davidbarone1970-dotcom
