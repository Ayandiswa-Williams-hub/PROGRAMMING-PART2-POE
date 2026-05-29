# PROGRAMMING-PART2-POE

# Cybersecurity Awareness Bot - Part 2

A modern WPF GUI Cybersecurity Chatbot with voice greeting, keyword recognition, sentiment detection, memory, and intelligent responses.

---

 Student Information
- **Name**: Ayandiswa Williams
- **Student Number**: [Your Student Number]

---

 Features Implemented (Part 2)

 Clean WPF GUI with dark cybersecurity theme
 Voice greeting on startup (`greeting.wav`)
 ASCII Art display
 Advanced Keyword Recognition (12+ cybersecurity topics)
 Random responses for each topic
 Sentiment Detection (Worried, Curious, Frustrated, Happy)
 Memory & Personalization (remembers name and favourite topic)
Smart conversation flow with follow-ups ("tell me more")
 Full question support (e.g. "What is phishing?")
 OOP Design with separate classes

 Prerequisites
- Visual Studio 2022
- .NET 8.0 Desktop Development
- Windows Operating System

How to Run the Project

1. Clone the repository:
   bash
   git clone https://github.com/Ayandiswa-Williams-hub/PROGRAMMING-PART2-POE.git
 2.  Open CybersecurityChatbot.sln in Visual Studio 2022.
Copy greeting.wav into the project root folder (same folder as MainWindow.xaml).
In Solution Explorer:
Right-click greeting.wav → Properties
Set Copy to Output Directory = Copy always

Build and Run (F5).
Audio Setup
Place the greeting.wav file in the root of the project folder and set it to Copy always.

 Screenshots
<img src="screenshot.png" alt="Cybersecurity Chatbot GUI">
(Add your screenshot here after running the app)

 Video Demonstration
Watch Demo Video
(Replace with your unlisted YouTube link)

PROGRAMMING-PART2-POE/
├── CybersecurityChatbot.sln
├── README.md
├── CybersecurityChatbot/
│   ├── MainWindow.xaml
│   ├── MainWindow.xaml.cs
│   ├── ChatBot.cs
│   ├── KeywordResponder.cs
│   ├── SentimentDetector.cs
│   ├── MemoryStore.cs
│   ├── AudioPlayer.cs
│   ├── greeting.wav
│   └── ...
└── .github/workflows/build.yml

