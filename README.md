🌍 Multilingual AI Voice Assistant

📌 Project Overview

The Multilingual AI Voice Assistant is an intelligent conversational application that enables users to communicate with an AI assistant using text or voice in multiple languages.

The system automatically:

✦Detects the user's language
✦Translates text to English
✦Generates AI responses using Ollama (Phi-3)
✦Performs sentiment analysis
✦Translates responses back to the user's language
✦Converts AI responses into speech

The application provides a complete multilingual conversational experience through an easy-to-use Streamlit interface.

🚀 Features

✅ Multilingual Text Chat

✅ Voice Input Support

✅ Automatic Language Detection

✅ Real-Time Translation

✅ AI-Powered Responses using Ollama

✅ Sentiment Analysis

✅ Text-to-Speech Response

✅ Chat History Management

✅ Multiple Indian Language Support

✅ Interactive Streamlit Dashboard

🛠️ Technologies Used

✦Python
✦Streamlit
✦Ollama
✦Phi-3 LLM
✦SpeechRecognition
✦Google Translator
✦gTTS (Google Text-to-Speech)
✦LangDetect
✦Audio Recorder Streamlit
✦Truststore

🧠 System Architecture
User Input
(Text / Voice)
       │
       ▼
Speech Recognition
       │
       ▼
Language Detection
       │
       ▼
Translate to English
       │
       ▼
Sentiment Analysis
       │
       ▼
Ollama (Phi-3)
       │
       ▼
AI Response
       │
       ▼
Translate Back
       │
       ▼
Text-to-Speech
       │
       ▼
Audio Output

🌐 Supported Languages

Language	Code
English	en
Tamil	ta
Hindi	hi
Telugu	te
Malayalam	ml
Kannada	kn
Bengali	bn
Gujarati	gu
Marathi	mr

✨ Key Functionalities

1. Voice-to-Text

Users can record their voice directly from the application.

Example:
வணக்கம், நீங்கள் எப்படி இருக்கிறீர்கள்?

Converts to:
Hello, how are you?

2. Language Detection

The application automatically identifies the user's language.

Example:
வணக்கம்

Detected Language:
ta

3. Translation Engine
 
Non-English text is automatically translated before sending it to the AI.

Example:
நீங்கள் யார்?

Translated:
Who are you?

4. Sentiment Analysis
5. 
The assistant classifies user sentiment into:

POSITIVE
NEGATIVE
NEUTRAL

Example:
Input:
I am very happy today.

Output:
POSITIVE

5. AI Conversation
The translated text is processed by the Phi-3 model running locally through Ollama.

Example:
Explain Artificial Intelligence.

AI generates a detailed response.

6. Response Translation
The AI response is translated back into the user's original language.

Example:
Tamil Input → English Processing → Tamil Response

7. Text-to-Speech
The final response is converted into natural speech.

Supported in multiple languages.

🎤 Example Workflow

User Voice Input
என்ன AI?

Language Detection
Tamil

Translation
What is AI?

AI Response
Artificial Intelligence is the simulation of human intelligence by machines.

Translation Back
செயற்கை நுண்ணறிவு என்பது மனித நுண்ணறிவை இயந்திரங்கள் மூலம் உருவகப்படுத்துவதாகும்.

Audio Output
AI response spoken in Tamil

📂 Project Structure
Multilingual-AI-Voice-Assistant/
│
├── app.py
├── requirements.txt
├── README.md
└── assets/

📊 Application Features Screen

The application includes:

✦Text Chat Interface
✦Voice Recording
✦Language Detection
✦Translation Panel
✦Sentiment Analysis
✦AI Response Generation
✦Audio Playback
✦Chat History
✦Clear Chat Button

🔥 Real-World Use Cases

✦Education
Multilingual learning assistant
Language practice

✦Customer Support
Multilingual chatbot

✦Accessibility
Voice-based interactions
Speech-enabled AI communication

✦Productivity
Personal AI assistant
Local private chatbot

🔮 Future Enhancements

✦Whisper Speech Recognition
✦RAG Integration
✦PDF Question Answering
✦Voice Cloning
✦Multiple Ollama Models
✦Conversation Memory
✦Offline Translation
✦Emotion Detection

👨‍💻 Author
Harish
Built with Streamlit, Ollama, NLP, Translation, Speech Recognition, and Text-to-Speech technologies to create a multilingual AI conversational assistant.
AI Agent Integration
