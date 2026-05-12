# Speech to Text

Python speech-to-text transcription using the `SpeechRecognition` library. Captures audio input from a microphone and outputs live transcriptions.

## Overview

`Speech-to-Text Test.ipynb` demonstrates microphone stream capture and transcription using Google's Speech Recognition API as the backend engine. Built as an early exploration of voice interface tooling.

> **Note:** The `speech_recognition` library's API bindings have evolved since this was written. Minor dependency updates may be required to run against current library versions.

## How to Run

```bash
pip install SpeechRecognition pyaudio
jupyter notebook "Speech-to-Text Test.ipynb"
```

Requires a connected microphone.

## Tech Stack
- Python 3
- `SpeechRecognition` — audio capture and transcription
- `pyaudio` — microphone stream interface
- Google Speech Recognition API (free tier)
