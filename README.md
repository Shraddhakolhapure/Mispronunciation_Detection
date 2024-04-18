
# Pronunciation Detection System
# Overview
This Python-based Pronunciation Detection System uses the CMU Pronouncing Dictionary and Google Speech Recognition to detect mispronunciations in spoken words. It provides real-time feedback on pronunciation accuracy and generates visualizations to analyze the results.

# Features
Real-time pronunciation detection using a microphone input.
Recognition of correct pronunciation and identification of mispronounced words.
Visualization of results through pie charts, confusion matrices, and BLEU scores.
Support for multiple languages (English, Marathi, etc.) using appropriate dictionaries.
# Dependencies
Python 3.x
Required Python libraries: speech_recognition, pyttsx3, nltk, matplotlib, numpy, scikit-learn, seaborn
# Installation
Clone the repository: git clone https://github.com/yourusername/pronunciation-detection.git
Install dependencies: pip install -r requirements.txt
Download additional NLTK resources: python -m nltk.downloader cmudict
# Usage
Run the main.py file: python main.py
Click on the "Start" button to initiate the pronunciation detection system.
Pronounce words into the microphone.
Listen to the system's feedback on pronunciation accuracy.
To exit the system, say "exit" or click on the close button.
