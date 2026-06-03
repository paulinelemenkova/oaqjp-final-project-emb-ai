# oaqjp-final-project-emb-ai-polina

## Emotion Detection Web Application

An AI-based web application that detects emotions from text using the **Watson NLP Library**.

## Project Overview

This project was developed as part of the IBM AI Application Development course final project. It implements an emotion detection system that analyses text and identifies the dominant emotion.

## Features

- Detects 5 emotions: **anger**, **disgust**, **fear**, **joy**, **sadness**
- Returns the **dominant emotion** for any given text
- Web interface built with **Flask**
- Error handling for blank/invalid inputs
- Unit tested with Python `unittest`

## Project Structure

```
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Tasks Completed

- ✅ Task 1: Cloned the project repository
- ✅ Task 2: Created emotion detection application using Watson NLP library
- ✅ Task 3: Formatted the output of the application
- ✅ Task 4: Packaged the application
- ✅ Task 5: Run Unit tests on the application
- ✅ Task 6: Web deployment of the application using Flask
- ✅ Task 7: Incorporated error handling
- ✅ Task 8: Run static code analysis

## How to Run

1. Install dependencies:
```bash
pip install flask requests
```

2. Start the Flask server:
```bash
python server.py
```

3. Open your browser and navigate to:
```
http://localhost:5000
```

## Technologies Used

- Python 3
- Flask
- Watson NLP EmotionPredict API
- HTML/CSS/JavaScript

## Author

Pauline Lemenkova
