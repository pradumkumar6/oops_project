# NLP App with Google Gemini Integration

This is an NLP (Natural Language Processing) application built in Python, utilizing Object-Oriented Programming (OOP) principles. The application integrates with Google’s Gemini API via the google.generativeai library to provide functionalities like sentiment analysis, language translation, and language detection.

The app includes a user authentication system, allowing users to register and log in before accessing NLP functionalities.

## Features

- Sentiment Analysis: Analyze the sentiment of a given text input.
- Language Translation: Translate input text into Hindi.
- Language Detection: Detect the language of the provided text input.
- User Authentication: Supports user registration and login functionality for accessing NLP features.

## Tech Stack

**Python:** Core programming language.

**Google Gemini API:** For NLP functionalities via the google.generativeai library.

**Object-Oriented Programming:** Structured the app in modular classes for scalability and maintainability.

## Installation

Install my-project with npm

```bash
pip install requirements.txt
python nlp_app.py


```

## Code Structure

**NLPModel Class:** Handles connection to the Google Gemini model.

**NLPApp Class:** Contains the main logic for user interaction, registration, login, and NLP tasks (sentiment analysis, language translation, language detection).

**Menu Methods:** Provides text-based menus for navigating between registration, login, and NLP functionalities.

## Future Improvements

**Database Integration:** Replace the in-memory dictionary storage with a database (e.g., SQLite) for user data persistence.

**Additional NLP Features:** Expand functionality to include text summarization, keyword extraction, or named entity recognition.

**Enhanced Error Handling:** Implement more comprehensive error handling and logging.
