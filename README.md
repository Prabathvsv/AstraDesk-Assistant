# AstraDesk – Your Personal Desktop Voice Assistant

AstraDesk is a smart, voice-enabled desktop assistant built with Python. It features an intuitive Tkinter GUI and supports a variety of voice commands—from playing YouTube videos to fetching Wikipedia summaries, telling jokes, opening apps, and more.

## 🎙 Speak. ✨ Automate. 🚀 Boost your productivity—right from your desktop.

![Screenshot 2025-05-30 132819](https://github.com/user-attachments/assets/0628117b-1288-4295-8d56-fdbfb0694ebb)


### FEATURES

- Voice-controlled interaction (speech recognition)
- Wikipedia integration for quick facts
- YouTube playback with just a voice command
- Google search and map location lookup
- Jokes on-demand with pyjokes
- Announces current time
- Launch local files or applications
- Clean GUI using Tkinter and Pillow
- Desktop notifications via plyer

### ⚙️ Tech Stack

| Category                 | Technology / Library       | Purpose                                       |
| ------------------------ | -------------------------- | --------------------------------------------- |
| **Programming Language** | Python 3.10+               | Core development language                     |
| **GUI Framework**        | Tkinter, Pillow            | Desktop UI and image handling                 |
| **Voice Recognition**    | SpeechRecognition, PyAudio | Convert spoken commands to text               |
| **Voice Output**         | pyttsx3                    | Text-to-speech (TTS) engine                   |
| **Web Automation**       | pywhatkit, webbrowser      | Play YouTube videos, search Google, open URLs |
| **Knowledge API**        | Wikipedia                  | Fetch summaries and info                      |
| **Entertainment**        | pyjokes                    | Fetch programming-related jokes               |
| **Notifications**        | Plyer                      | Cross-platform desktop notifications          |
| **Concurrency**          | threading                  | Non-blocking voice loop alongside GUI         |
| **Others**               | datetime, os               | Time queries, file system operations          |


### SAMPLE VOICE COMMANDS

- "Play Shape of You" → Plays the song on YouTube
- "Who is Ada Lovelace?" → Wikipedia summary
- "Open YouTube" → Opens youtube.com
- "Search artificial intelligence" → Google search
- "Where is Eiffel Tower" → Opens Maps
- "Tell me a joke" → Says a joke
- "What time is it?" → Announces time
- "Open code" → Opens a local file

### PROJECT STRUCTURE

AstraDesk/<br>
├── main2.py<br>
├── requirements.txt<br>
├── a wallpaper for voice assistant.jpg<br>
├── a mic which have vibrations.jpg<br>
└── README.md<br>


### LICENSE

This project is licensed under the MIT License.
You are free to use, modify, and distribute—with credit to the original creator.

### CONTRIBUTING

1. Fork the repository
2. Create a branch: git checkout -b feature/your-feature
3. Commit changes: git commit -m "Add new feature"
4. Push branch: git push origin feature/your-feature
5. Open a pull request
