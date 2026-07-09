# Emotion Detector Application

An AI-based web application that detects and analyzes emotional states from text inputs. Built using **Python**, **Flask**, and the **Watson NLP** library, this project demonstrates the implementation of a complete software development lifecycle—including modular package creation, formatting API responses, unit testing, error handling, web deployment, and static code analysis.

---

## 🌟 Features

*   **AI-Powered Emotion Detection:** Analyzes text using Watson NLP to compute scores for five core emotions: `anger`, `disgust`, `fear`, `joy`, and `sadness`.
*   **Dominant Emotion Identification:** Automatically determines which emotion has the highest score.
*   **Robust Error Handling:** Seamlessly handles empty or invalid inputs (HTTP Status Code 400) by returning clean error notifications without crashing the server.
*   **Dynamic Web Interface:** A user-friendly Flask-based UI allowing users to input statements and view formatted real-time emotional analysis.
*   **High Code Quality:** Fully compliant with Python standards, achieving a perfect `10/10` score on `pylint` static code analysis.

---

## 🛠️ Project Structure

```text
EmotionDetector/
│
├── EmotionDetection/               # Core application package
│   ├── __init__.py                 # Initializes the directory as a Python package
│   └── emotion_detection.py        # Logic for Watson NLP API requests & formatting
│
├── templates/                      # HTML templates for the web interface
│   └── index.html                  # Main UI page
│
├── static/                         # Static assets for frontend styling
│   └── mywebstyle.css              # Custom stylesheet
│
├── server.py                       # Flask application deployment and routing backend
├── test_emotion_detection.py       # Automated unit tests using unittest
└── README.md                       # Project documentation and details
