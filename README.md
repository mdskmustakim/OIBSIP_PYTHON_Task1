# 🎙️ Mustak's Voice Assistant

A simple Python-based voice assistant that listens to voice commands, converts speech into text, performs basic tasks, and responds using text-to-speech.

The assistant can tell the current time and date, open websites, perform Google searches, and respond to basic voice commands.

---

## ✨ Features

- 🎤 Voice command recognition
- 🔊 Text-to-speech responses
- 🕐 Current time
- 📅 Current date
- 🌐 Open Google
- ▶️ Open YouTube
- 🔎 Search Google using voice
- 👋 Greeting response
- ❌ Exit command
- 🛡️ Basic error handling

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| SpeechRecognition | Converts speech into text |
| PyAudio | Provides microphone input |
| pyttsx3 | Converts text into speech |
| datetime | Gets current date and time |
| webbrowser | Opens websites and search results |

---

## 📂 Project Structure

```text
Voice-Assistant/
│
├── VoiceRecognition.py
├── requirements.txt
├── README.md
└── .gitignore

⚙️ Requirements

Before running the project, make sure you have:

Python 3.x
A working microphone
Internet connection
Required Python libraries

📦 Installation

1. Clone the repository
git clone https://github.com/YOUR-USERNAME/mustak-voice-assistant.git

2. Open the project folder
cd mustak-voice-assistant

3. Install required libraries
pip install -r requirements.txt

▶️ How to Run
Run the following command:
python VoiceRecognition.py

The assistant will greet you and start listening for voice commands.


🎤 Available Voice Commands

Voice Command	                Action

Hello	                    Greets the user
Tell me the time	       Tells the current time
Tell me the date	        Tells today's date
Open Google	                    Opens Google
Open YouTube	                Opens YouTube
Search for Python	        Searches Google for Python
Exit	                        Stops the assistant

Example

Say:

        Search for Python programming

The assistant will open a Google search for:

        Python programming


🧠 How It Works

The assistant follows a simple voice-processing pipeline:

User speaks
     ↓
Microphone captures audio
     ↓
SpeechRecognition processes the audio
     ↓
Google Speech Recognition converts speech to text
     ↓
Python checks the command
     ↓
Requested action is performed
     ↓
pyttsx3 generates the voice response

🛡️ Error Handling

The application handles common situations such as:

No voice input within the timeout period
Speech that cannot be understood
Problems with the speech recognition service

This prevents the program from crashing during normal usage.


🚀 Future Improvements

The project can be extended with additional features such as:

🌤️ Weather information
🎵 Music playback
📰 News updates
📧 Email sending
📱 Application launching
🤖 AI-powered conversations
🔐 User authentication
⏰ Reminders and alarms
🔍 More advanced voice commands

🤝 Contributing

Contributions and suggestions are welcome.

If you would like to improve this project:

1.Fork the repository
2.Create a new branch
3.Make your changes
4.Commit your changes
5.Open a Pull Request


👨‍💻 Author

MD SK MUSTAKIM

B-Tech CSE(AI&ML) ENGINEER