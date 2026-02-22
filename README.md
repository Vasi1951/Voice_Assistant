🎙️ Voice Assistant (Colab Compatible Version)
📌 Project Overview

This project is a Python-based Voice Assistant that processes user commands and responds using text-to-speech.
It can search Wikipedia, open websites, and handle basic conversational queries.

The original version was built using pyttsx3 and microphone input.
This version is modified to run smoothly in Google Colab using gTTS and manual command input.

🚀 Features

🔎 Wikipedia search integration

🗣️ Text-to-Speech output using gTTS

🌐 Open common websites (YouTube, Google, GitHub)

💬 Basic conversational responses

☁️ Google Colab compatible

🛠️ Tech Stack

Python

SpeechRecognition

Wikipedia API

gTTS (Google Text-to-Speech)

Google Colab

📂 Project Structure
Voice-Assistant/
│
├── Voice_Assistant.ipynb
├── README.md
▶️ How to Run (Google Colab)

Open the notebook in Google Colab.

Run the installation cell:

!pip install SpeechRecognition
!pip install wikipedia
!pip install gTTS

Run all cells in order.

Type your command when prompted.

Example commands:

wikipedia virat kohli
open youtube
open github
exit
⚠️ Limitations

Microphone input is disabled in Colab (uses manual text input instead).

pyttsx3 is replaced with gTTS for cloud compatibility.

Local disk access is not supported in Colab.

📈 Future Improvements

Add real-time microphone support (local system version)

Integrate OpenAI / ChatGPT API

Add reminder and task scheduling feature

Improve NLP command understanding

👨‍💻 Author

M. Vashisht
Diploma in AI & ML
Python Developer
