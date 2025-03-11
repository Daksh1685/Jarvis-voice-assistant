# Voice Assistant - Jarvis

## Introduction
This is a Python-based voice assistant named "Jarvis" that can perform various tasks such as searching Wikipedia, opening websites, playing music, checking the time, and sending emails. The assistant takes voice commands as input and responds accordingly using text-to-speech (TTS) functionality.

## Features
- Greets the user based on the time of the day.
- Recognizes voice commands using speech recognition.
- Searches Wikipedia and reads out a summary.
- Opens popular websites like YouTube, Google, and Stack Overflow.
- Plays music from a predefined directory.
- Provides the current time.
- Opens Visual Studio Code.
- Sends emails using SMTP.

## Requirements
To run this project, you need to install the following Python libraries:

```sh
pip install pyttsx3
pip install speechRecognition
pip install wikipedia
```

## Installation
1. Clone the repository or copy the script to your local machine.
2. Install the required dependencies using the commands listed above.
3. Update the `sendEmail` function with your Gmail credentials.
4. Run the script using:

```sh
python jarvis.py
```

## How It Works
1. The script initializes the text-to-speech engine and sets the voice properties.
2. It greets the user based on the current time.
3. It continuously listens for voice commands and processes them.
4. Depending on the command, it executes the appropriate function, such as opening a website, playing music, or sending an email.

## Commands
You can use the following voice commands:
- "Search Wikipedia for [query]"
- "Open YouTube"
- "Open Google"
- "Open Stack Overflow"
- "Play music"
- "What is the time?"
- "Open Code"
- "Email to Harry"

## Notes
- Ensure your microphone is working properly.
- Update the paths to your music directory and VS Code executable as needed.
- Modify the email credentials before sending an email to avoid authentication issues.
