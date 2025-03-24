# Speech-to-Text Translator

## Overview
This Python script converts spoken words into text using Google's Speech Recognition API and then translates the recognized text into German using the `translate` library.

## Features
- Captures speech from the microphone.
- Converts speech to text using Google's Speech Recognition API.
- Translates the recognized text into German.
- Displays the original and translated text in the console.

## Requirements
Ensure you have the following Python libraries installed:

```sh
pip install SpeechRecognition translate

For some systems (especially Windows), you may need to manually install pyaudio:

Download from PyAudio Releases

Install using:
pip install <path-to-downloaded-file>.whl

Usage
Run the script:
python translator.py

Speak into the microphone when prompted.

The recognized text and its German translation will be displayed.

Known Issues
The translation library translate may require an internet connection.

Some accents or background noise may cause incorrect speech recognition.

If the translation fails, consider using googletrans instead.

License
This project is open-source and available under the MIT License.

Author
Paul Mugambi
