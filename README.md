# chand-voice_assistance-
🗣️ A Python-based AI voice assistant with speech recognition, text-to-speech, GUI, web search, and basic automation features.


# 🗣️ CHAND – AI Voice Assistant

CHAND is a Python-based AI voice assistant that allows users to interact with the computer using voice commands. It uses speech recognition to understand user commands and text-to-speech technology to respond through voice.

The project also includes a simple **Tkinter GUI** that displays the assistant's responses, listening status, and interaction history.

## ✨ Features

- 🎙️ Voice-based interaction
- 🗣️ Text-to-speech responses
- 🔍 Google search using voice commands
- 📺 Open YouTube and search for videos
- 📚 Search information using Wikipedia
- 🕐 Tell the current time and date
- 🧮 Perform basic mathematical calculations
- 📝 Open Notepad
- 🧮 Open Calculator
- 🎵 Open YouTube Music
- 🖥️ Simple Tkinter graphical interface
- 🛑 Voice commands to stop or exit the assistant

## 🛠️ Technologies Used

- **Python**
- **SpeechRecognition** – Converts voice input into text
- **PyAudio** – Provides microphone access
- **pyttsx3** – Converts text into speech
- **Tkinter** – Creates the graphical user interface
- **Wikipedia** – Retrieves information from Wikipedia
- **Webbrowser** – Opens websites and web searches

## 📂 Project Structure

```text
CHAND-AI-Voice-Assistant/
│
├── voice assistance.py
├── gui.py
└── README.md
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/CHAND-AI-Voice-Assistant.git
```

### 2. Open the Project Folder

```bash
cd CHAND-AI-Voice-Assistant
```

### 3. Install Required Libraries

```bash
pip install SpeechRecognition pyttsx3 wikipedia
```

If PyAudio is required for microphone input:

```bash
pip install PyAudio
```

## ▶️ How to Run

Run the main Python file:

```bash
python "voice assistance.py"
```

The CHAND GUI will open and the voice assistant will start.

Say:

```text
Hello
```

to activate the assistant and then give your voice command.

## 🎤 Example Voice Commands

You can try commands such as:

```text
Hello
What is the time?
What is today's date?
Open Google
Open YouTube
Search Python programming on Google
Search Machine Learning on Wikipedia
Open Notepad
Open Calculator
Play music
Calculate 25 plus 15
Stop Chand
```

## 🧮 Calculator

CHAND can perform basic mathematical operations including:

- Addition
- Subtraction
- Multiplication
- Division
- Percentage
- Square
- Square root
- Power
- Remainder

Example:

```text
Calculate 25 plus 15
```

CHAND will process the calculation and provide the result through voice and the GUI.

## 🖥️ GUI

The project includes a Tkinter-based graphical interface that displays:

- Assistant name
- Assistant responses
- User commands
- Listening status
- Start/Running status

## 🔄 How It Works

```text
User Voice
     ↓
Microphone
     ↓
Speech Recognition
     ↓
Command Processing
     ↓
Task Execution
     ↓
CHAND Response
     ↓
Text-to-Speech + GUI
```

## 🎯 Project Objective

The main objective of this project is to build a simple voice-controlled assistant using Python and understand how different Python libraries can be integrated to perform voice recognition, speech synthesis, web interaction, calculations, and GUI development.

## 🚀 Future Improvements

- Add more voice commands
- Add weather information
- Add email functionality
- Add reminders and alarms
- Improve natural language understanding
- Add more applications and system controls
- Improve the GUI design
- Add support for multiple languages

## 👩‍💻 Author

**Chandrika Gajjela**

This project was developed as a Python project to practice voice recognition, automation, GUI development, and Python programming.

## 📄 License

This project is created for educational and learning purposes.
