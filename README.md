# Emotion Detector

An AI-based web application that detects emotions (anger, disgust, fear, joy, sadness) in text using the Watson NLP Emotion Predict service, and reports the dominant emotion.

## Project structure
- `EmotionDetection/emotion_detection.py` - `emotion_detector()` function that calls Watson NLP and formats the result
- `EmotionDetection/__init__.py` - package initializer
- `test_emotion_detection.py` - unit tests
- `server.py` - Flask web deployment

## Run
```
python3.11 -m pip install requests flask
python3.11 server.py
```
Then open http://localhost:5000
