# Ten Days of Voice Agents 2025

A professional and feature-rich implementation for the **Murf AI – Ten Days of Voice Agents Challenge**. This repository contains a continuously evolving voice AI agent system built using industry-grade tools and best practices.

---

## 🚀 Overview

This project demonstrates the development of an advanced **real-time Voice AI Agent**, integrating cutting-edge speech, language, and streaming technologies. The goal is to build a highly interactive, natural, and responsive agent with new capabilities added daily throughout the 10-day challenge.

The system is structured with a **Python backend** for voice intelligence and a **Next.js frontend** for seamless user interaction.

---

## 🎯 Project Goals

* Build and refine a **LiveKit-powered voice agent**
* Integrate **Murf Falcon TTS** for ultra-fast speech output
* Use **Deepgram Nova-3 STT** for accurate transcription
* Power reasoning with **Google Gemini 2.5 Flash**
* Add new abilities, personas, and tools each day
* Deliver a production-ready full-stack voice AI experience

---

## 🧠 Features

### ✔ Real-Time Voice AI

* Listen → Understand → Think → Speak loop
* Ultra-low-latency streaming with LiveKit Agents

### ✔ High-Quality Text-to-Speech

* Powered by **Murf Falcon TTS**
* Natural, expressive, fast responses

### ✔ Accurate Speech Recognition

* Deepgram Nova-3 STT
* Handles accents, noise, and natural speech

### ✔ Advanced Language Reasoning

* Gemini 2.5 Flash
* Useful for Q&A, explanations, and conversations

### ✔ Modular & Extensible

* Add new tools
* Add personas
* Add workflows and domain-specific logic
* Daily updates following challenge tasks

---

## 🏗 Tech Stack

### **Backend (Python)**

* LiveKit Agents
* Murf Falcon TTS
* Deepgram STT
* Gemini LLM
* Turn Detection & VAD
* Async event-driven architecture

### **Frontend (Next.js)**

* LiveKit React SDK
* Audio visualization
* Microphone streaming
* Clean, modern UI (light/dark)

---

## 📁 Project Structure

```
/backend        # Python agent: STT, LLM, TTS, routing, personas
/frontend       # Next.js frontend: UI + WebRTC streaming
/challenges     # Daily task notes and progress
/start_app.sh   # Run all services easily
```

---

## ▶️ Running the Project

### **1. Start LiveKit Server (local)**

```
livekit-server --dev
```

### **2. Start Backend**

```
cd backend
uv run python src/agent.py dev
```

### **3. Start Frontend**

```
cd frontend
pnpm dev
```

Open: **[http://localhost:3000](http://localhost:3000)**

---

## 📅 Daily Progress

This repository is updated every day with:

* New features
* Persona enhancements
* Conversation improvements
* Tools & integrations
* Performance tuning

Follow the commits to track progress.

---

## 🤝 Contributing

This is a challenge project but contributions, feedback, and ideas are welcome.

---

## 📜 License

MIT License — free to use, modify, and build upon.

---

## ⭐ Acknowledgements

* **Murf AI** for Falcon TTS
* **LiveKit** for real-time agent framework
* **Deepgram** for STT
* **Google Gemini** for reasoning capabilities

---

### 💬 Thank you for visiting this repository.

Stay tuned for daily updates as this voice AI evolves!
