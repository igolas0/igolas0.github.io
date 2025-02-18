# Longevity Health App

This repo shows how to deploy a simple chatbot.

Link to demo: https://igolas0.github.io/

In this repository the front end side is covered.

The backend site is covered in this other repository:
https://github.com/igolas0/AI-App-Backend

## Frontend Application Summary

Purpose: A health and longevity chatbot interface that connects to a backend API (hosted on PythonAnywhere) to deliver AI-generated health tips using an LLM (Mistral-7B via Hugging Face).
Core Features

    Chat Interface:

        Users input health-related questions (e.g., "Best diet for longevity?").

        Displays a conversational history with user prompts and bot responses.


### Dependencies

    Backend requires flask-cors to allow cross-origin requests from the frontend.

### Configuration

    API Endpoint: Configured in index.html to point to https://[USERNAME].pythonanywhere.com/chat.

    Security:

        CORS enabled on the backend to accept requests from any origin (simplified for MVP).

        Hugging Face token stored securely via PythonAnywhere environment variables.

### Deployment

    Frontend:

        Static files (HTML/CSS/JS) hosted on GitHub Pages.

    Backend:

        Flask app deployed on PythonAnywhere with environment variables for tokens.

### Quick Start Guide

    Clone the GitHub repo.

    Update index.html with your PythonAnywhere API URL.

    Deploy frontend to GitHub Pages (or to a static hosting service of your choice).
