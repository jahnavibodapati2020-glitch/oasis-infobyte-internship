# Voice Assistant using Python

## Overview
This project is a basic Voice Assistant developed in Python that can recognize user voice commands and respond using text-to-speech. It demonstrates fundamental concepts of speech recognition, automation, and human-computer interaction.

## Key Features
- Voice command recognition using SpeechRecognition
- Text-to-speech response using pyttsx3
- Provides current time and date
- Performs web search using default browser
- Handles basic user interactions
- Simple and modular code structure

## Technologies Used
- Python
- SpeechRecognition (for voice input)
- pyttsx3 (for speech output)
- datetime (for time and date)
- webbrowser (for search functionality)
- pywhatkit(for automation of tasks)

## Installation
### Prerequisites
- Python 3.x installed
- Working microphone

### Steps
1. Clone the repository:
   git clone https://github.com/jahnavibodapati2020-glitch/oasis-infobyte-internship/tree/main/VoiceAssistant

2. Install dependencies:
   pip install SpeechRecognition pyttsx3 pyaudio

   If PyAudio installation fails:
   pip install pipwin
   pipwin install pyaudio
   
## Execution

Run the following command:
python voice_assistant.py

## Usage
* Say "Hello" → Assistant greets the user
* Say "Time" → Returns current system time
* Say "Date" → Returns current date
* Say "Search" → Opens Google search
* Say "Spotify" → Opens Spotify
* Say "WhatsApp"→ Opens WhatsApp
* Say "Play"→ Plays a song that user specifies
* Say "Exit" or "Stop" → Terminates the program

## Project Structure
voice_assistant.py   # Main application file
README.md            # Project documentation

## Skills Demonstrated
* Speech Recognition
* Text-to-Speech Processing
* Python Programming
* API Integration (Google Speech Recognition)
* Error Handling
* User Interaction Design

## Future Enhancements
* Add Natural Language Processing (NLP)
* Integrate weather API
* Email automation
* GUI-based interface
* Smart assistant features

## Author
Jahnavi
