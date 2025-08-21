# 🎯 Sentiment & Emotion Detection from Text and Audio

## 📖 Overview
This project is a **multimodal AI system** that detects **sentiment** (positive, negative, neutral) and **emotion** (joy, sadness, anger, fear, surprise, disgust, etc.) from both **text** and **audio inputs**.  
It combines **Natural Language Processing (NLP)** and **Speech Processing** to analyze human communication in multiple formats.  

The system is powered by **Hugging Face Transformers** for NLP-based classification, **OpenAI Whisper** for robust speech-to-text transcription, and **Gradio** for an interactive browser-based interface.  
It is implemented and deployed in **Google Colab** with support for GPU acceleration.

---

## ⚙️ Tech Stack
- **Python 3.10+** – Core programming language  
- **Hugging Face Transformers** – Pre-trained models for sentiment & emotion detection  
- **OpenAI Whisper** – Speech-to-text for audio input  
- **PyTorch** – Deep learning backend for model inference  
- **Librosa** – Audio preprocessing for Whisper  
- **Gradio** – Web-based UI for text/audio input and results visualization  
- **Google Colab** – Development and deployment environment  

---

## 🚀 Features
- Accepts **text input** for direct sentiment & emotion analysis  
- Accepts **audio input** (upload/record) and converts it into text for analysis  
- Supports **multilingual audio transcription** using Whisper  
- Outputs both **sentiment and emotion labels with confidence scores**  
- Interactive **browser-based UI** with separate tabs for text and audio  



## 🛠️ Installation
This project is designed to run in **Google Colab**.  
In a new Colab notebook, install dependencies:

```bash
!pip install gradio transformers torch librosa git+https://github.com/openai/whisper.git
