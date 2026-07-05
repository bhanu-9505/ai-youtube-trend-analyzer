# 🚀 AI YouTube Trend Analyzer

An AI-powered application that scrapes YouTube videos from one or more channels, extracts transcripts, and generates trend analysis using multi-agent AI.

---

## 📌 Features

- 🎥 Scrape YouTube videos using Bright Data
- 📝 Automatically extract video transcripts
- 🤖 Multi-agent analysis with CrewAI
- 🦙 Local LLM support using Ollama (Llama 3.2)
- 📊 Identify trends across multiple videos
- 😊 Analyze sentiment and speaker tone
- 🔑 Detect recurring keywords and themes
- 🌐 Interactive Streamlit web application

---

## 🛠 Tech Stack

- Python
- Streamlit
- CrewAI
- Bright Data
- Ollama
- Llama 3.2
- YAML
- dotenv

---

## 📂 Project Structure

```
.
├── app.py
├── brightdata_scrapper.py
├── config.yaml
├── assets/
├── transcripts/
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/bhanu-9505/ai-youtube-trend-analyzer.git

cd ai-youtube-trend-analyzer
```

### Create virtual environment

```bash
python -m venv .venv
```

Activate

Mac/Linux

```bash
source .venv/bin/activate
```

Windows

```bash
.venv\Scripts\activate
```

---

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure Environment Variables

Create a `.env` file.

```env
BRIGHT_DATA_API_KEY=your_brightdata_api_key
```

> This project uses a **local Ollama model**, so no OpenAI API key is required.

---

## 🦙 Install Ollama

Install Ollama

https://ollama.com

Download the model

```bash
ollama pull llama3.2
```

Start Ollama

```bash
ollama serve
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 📸 Screenshots

### Home Page

(Add screenshot here)

### Video Extraction

(Add screenshot here)

### Generated Analysis

(Add screenshot here)

---

## 🔄 Workflow

1. Enter YouTube channel URL
2. Bright Data scrapes recent videos
3. Transcripts are extracted
4. CrewAI agents analyze content
5. Ollama generates trend insights
6. Results are displayed in Streamlit

---

## ✨ Improvements Added

Compared to the original implementation:

- ✅ Integrated Ollama (Llama 3.2) for local inference
- ✅ Removed dependency on paid OpenAI API
- ✅ Configured local LLM support
- ✅ Improved setup for easier deployment
- ✅ Updated environment configuration

---

## 🚀 Future Improvements

- PDF report export
- Word cloud visualization
- Sentiment charts
- Trending keyword dashboard
- Multi-channel comparison
- AI chatbot for transcript Q&A
- Docker deployment

---

## 👨‍💻 Author

**Bhanu Nayak**

GitHub:
https://github.com/bhanu-9505

---

## ⭐ If you found this project useful

Please consider giving it a ⭐ on GitHub.
