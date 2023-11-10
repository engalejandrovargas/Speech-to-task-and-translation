
# Speech Translation with IBM Watson Language Translator and Google Speech Recognition

This project leverages the power of IBM Watson Language Translator and Google Speech Recognition to perform real-time speech translation. The Python script continuously records audio input, recognizes speech using Google Speech Recognition, and then translates the recognized text from English to Japanese using IBM Watson Language Translator.

## Features
- Real-time audio recording and translation
- Utilizes Google Speech Recognition for speech-to-text
- Integrates IBM Watson Language Translator for language translation
- Easy setup with IBM Watson Language Translator API credentials

## Prerequisites
Before running the script, make sure you have the following prerequisites installed:
- `ibm_watson` library
- `ibm_cloud_sdk_core` library
- `speech_recognition` library
- `pydub` library
- API key for IBM Watson Language Translator
- IBM Watson Language Translator service URL

## Setup
1. Install the required libraries using the following:
   ```bash
   pip install ibm_watson ibm_cloud_sdk_core speech_recognition pydub
   Replace API_key and url with your IBM Watson Language Translator API credentials.

## Usage
Run the script, and it will continuously record audio, recognize speech, and translate it to Japanese. Adjust the model_id in the translation part according to your language pair.
