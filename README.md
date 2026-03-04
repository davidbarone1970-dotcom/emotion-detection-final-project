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
