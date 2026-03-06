# VoxAgent
Real-time voice AI pipeline for BFSI workflows — Whisper STT + LLaMA 3.3-70B via Groq + gTTS

# 🎙️ VoxAgent — Real-Time Voice AI Pipeline

End-to-end voice AI agent that listens, thinks, and speaks back in real time. Built with BFSI workflows in mind — simulating intelligent voice assistants for loan queries, insurance support, and customer onboarding.

## 🧠 Pipeline
```
Audio Input (Mic / File)
        ↓
  Whisper (STT) — Speech Recognition
        ↓
  LLaMA 3.3-70B-Versatile via Groq API — LLM Response
        ↓
  gTTS — Text to Speech
        ↓
  Audio + Text Output via Gradio UI
```

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Speech-to-Text | OpenAI Whisper |
| LLM Inference | LLaMA 3.3-70B via Groq API |
| Text-to-Speech | gTTS |
| UI | Gradio |
| Language | Python |

## 💼 BFSI Use Case
Designed to simulate production voice AI pipelines used in:
- 🏦 Loan query assistance
- 📋 Insurance policy support
- 🔐 Digital onboarding conversations

## ⚙️ Setup
```bash
git clone https://github.com/baneXP/VoxAgent.git
cd VoxAgent
pip install -r requirements.txt
```
Get a free API key at [console.groq.com](https://console.groq.com), set it in `voice_to_voice_chatbot.py`, then:
```bash
python voice_to_voice_chatbot.py
```

## 👤 Author
**Satyam Sharma**
• [GitHub](https://github.com/baneXP) 
• [LinkedIn](https://linkedin.com/in/sharmasatyam01)
