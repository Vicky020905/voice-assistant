# Voice Assistant Project

A voice-controlled AI assistant built with Python that uses natural language processing and text-to-speech capabilities.

## Requirements

```
flet>=0.21.0
asyncio
pocketsphinx>=0.1.15
SpeechRecognition>=3.10.0
groq>=0.3.0
elevenlabs>=0.3.0
webbrowser
datetime
threading
```

## API Keys Required

You will need to obtain API keys for:
- ElevenLabs - For text-to-speech conversion
- Groq - For AI language model access

## Setup

1. Install the required packages:
```bash
pip install -r requirements.txt
```

2. Set up your API keys:
- Add your ElevenLabs API key in the code where indicated
- Add your Groq API key in the code where indicated

3. Run the application:
```bash
python main.py
```

## Features

- Wake word detection ("beam")
- Voice command recognition
- Natural language processing with Groq AI
- Text-to-speech output with ElevenLabs
- Application/website opening capabilities
- Interactive UI with Flet framework

## Supported Commands

- Open various applications (Chrome, VS Code, Notepad, Calculator)
- Open websites (YouTube, Google, WhatsApp Web, Telegram Web)
- Natural conversations with AI assistant
- Time-aware responses

## Note

Make sure you have a working microphone connected to your system for voice input functionality.
