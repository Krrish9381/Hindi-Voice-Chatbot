# 🎙️ Hindi Voice Agent with Emotional Responses

An intelligent Hindi voice assistant that listens, understands, and responds with **emotionally expressive speech**. This project demonstrates a complete pipeline from speech input to emotionally rich voice output.

> ⚠️ Note: This project is currently implemented in a Jupyter Notebook (`.ipynb`) format.

---

## 🚀 Features

* 🗣️ **Hindi Speech Recognition** using Whisper
* 🧠 **LLM-Powered Responses** using NVIDIA LLM
* 🎭 **Emotion-Aware Replies** (happy, sad, neutral, etc.)
* 🔊 **Expressive Voice Output** using Fish Audio
* 🌐 **Interactive UI** using Gradio inside notebook
* ⚡ End-to-end voice interaction pipeline

---

## 🏗️ Tech Stack

* **UI:** Gradio (Notebook-based)
* **Speech-to-Text:** Whisper
* **Language Model:** NVIDIA LLM
* **Text-to-Speech:** Fish Audio
* **Environment:** Jupyter Notebook / Python

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/hindi-voice-agent.git

# Navigate into the project
cd hindi-voice-agent

# Install dependencies
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Option 1: Run Locally (Jupyter Notebook)

```bash
jupyter notebook
```

1. Open the `.ipynb` file
2. Run all cells step by step
3. Use the Gradio interface inside the notebook

---

### Option 2: Run in Google Colab

1. Upload the `.ipynb` file to Colab
2. Install required dependencies in a cell:

   ```python
   !pip install -r requirements.txt
   ```
3. Run all cells
4. Interact with the voice agent

---

## 📁 Project Structure

```
├── hindi_voice_agent.ipynb   # Main notebook
├── requirements.txt          # Dependencies (if added)
└── README.md                 # Project documentation
```

---

## 🔄 Workflow

1. 🎤 User speaks in Hindi
2. 📝 Whisper converts speech → text
3. 🧠 NVIDIA LLM generates response
4. 🎭 Emotion is inferred
5. 🔊 Fish Audio converts text → expressive speech
6. 🌐 Output shown via Gradio

---

## 🎯 Use Cases

* 🧑‍🏫 Hindi learning assistant
* 🤖 Emotion-aware conversational AI
* 📞 Voice-based interaction systems
* ♿ Accessibility tools

---

## 🔮 Future Improvements

* Convert notebook → full Python app (`app.py`)
* Deploy as a web app
* Add multilingual support
* Improve emotion detection accuracy

---

## 🤝 Contributing

Feel free to fork this repository and improve it!

---

## 📜 License

MIT License

---

## 🙌 Acknowledgements

* OpenAI Whisper
* NVIDIA LLM
* Fish Audio
* Gradio

---

⭐ If you found this useful, please star the repo!
