# 🎙️ Voice Translator App

A simple and interactive voice translation tool built using Python. Speak any phrase, translate it to a desired language, and hear the translated phrase spoken back to you!

---

## ✨ Features

- 🎤 **Speech Recognition** using your microphone
- 🌐 **Language Translation** between any two supported languages
- 🔊 **Text-to-Speech** to speak the translated output
- 🖥️ **GUI Interface** using Tkinter for easy interaction
- 🎮 **Audio Playback** with Pygame

---

## 📦 Dependencies

Make sure you have the following Python packages installed:

pip install SpeechRecognition gTTS pygame translate

You'll also need to have PyAudio installed for microphone access:
For Windows:
pip install pipwin
pipwin install pyaudio
For macOS:
brew install portaudio
pip install pyaudio
For Linux (Debian-based):
sudo apt-get install portaudio19-dev
pip install pyaudio


🚀 How to Run
Clone the repository:
git clone https://github.com/ChAtulKumarPrusty/VoiceTranslator.git
cd voice-translator
Run the Python script:
python your_script_name.py
A prompt will appear asking for the source and destination language codes (e.g., en, fr, es, etc.). After that, just start speaking!

🌍 Language Codes
Some common language codes you can use:


Language	Code
English	en
Spanish	es
French	fr
German	de
Hindi	hi
Chinese	zh
Japanese	ja

You can find the full list of supported language codes in the Google Translate documentation.

🧠 How It Works
Captures voice input from the user via microphone.
Uses SpeechRecognition with Google’s speech-to-text API to convert speech to text.
Translates the text using the translate module.
Converts the translated text to speech using gTTS.
Plays the audio using pygame.

📌 Note
Requires an internet connection for Google APIs (speech recognition and translation).
Ensure your microphone is properly connected and working.
Background noise can affect speech recognition accuracy.

👨‍💻 Author
Developed with ❤️ Ch Atul Kumar Prusty

Let me know if you want me to add:
- A GIF demo
- Badge icons (stars, forks, etc.)
- Project folder structure explanation

Happy uploading! 🚀
