# Hindi Voice Chatbot

# 🎙️ Hindi Voice Assistant

A Hindi Voice Assistant built using **OpenAI Whisper**, **NVIDIA Llama**, **Gradio**, and **Edge TTS**. The application accepts spoken Hindi input, converts it to text, generates an intelligent response using an LLM, and returns the response as both text and speech.

---

## 🚀 Features

- 🎤 Speech-to-Text using OpenAI Whisper
- 🤖 Hindi conversation using NVIDIA Llama API
- 🔊 Text-to-Speech using Edge TTS
- 🌐 Interactive web interface with Gradio
- 🇮🇳 Optimized for Hindi language interaction

---

## 🛠️ Tech Stack

- Python
- OpenAI Whisper
- NVIDIA AI Endpoints (Llama)
- Edge TTS
- Gradio
- LangChain
- FFmpeg

---

## 📂 Project Structure

```
Hindi-Voice-Agent/
│
├── Hindi_voice_agent.ipynb
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Krrish9381/Hindi-Voice-Chatbot.git
cd Hindi-Voice-Chatbot
```

Install dependencies:

```bash
pip install -r requirements.txt
```

If you are using Google Colab, install the required packages:

```bash
pip install openai-whisper
pip install gradio
pip install ffmpeg-python
pip install langchain-nvidia-ai-endpoints
pip install python-dotenv
pip install edge-tts
```

---

## 🔑 Environment Variables

Create a `.env` file and add your NVIDIA API key:

```env
NVIDIA_API_KEY=YOUR_API_KEY
```

---

## ▶️ Usage

Run the notebook or launch the Gradio interface.

Workflow:

```
🎤 User speaks in Hindi
        │
        ▼
OpenAI Whisper
        │
        ▼
Hindi Transcript
        │
        ▼
NVIDIA Llama
        │
        ▼
LLM Response
        │
        ▼
Edge TTS
        │
        ▼
🔊 Hindi Speech Output
```

---

## 📸 Demo

Example:

**Input (Speech):**

> "आज का मौसम कैसा है?"

**Transcript:**

> आज का मौसम कैसा है?

**LLM Response:**

> आज मौसम सामान्य रहने की संभावना है।

**Speech Output:**

Generated as an audio response in Hindi.

---

## 📦 Requirements

- Python 3.10+
- Internet connection
- NVIDIA API Key

---

## 🎯 Future Improvements

- Support multiple Indian languages
- Conversation history
- Voice selection
- Faster streaming responses
- Deployment on Hugging Face Spaces
- Mobile-friendly interface

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Krrish**

GitHub: https://github.com/Krrish9381

---

⭐ If you found this project useful, please consider giving it a star!
