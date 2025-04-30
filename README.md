# Kinyarwanda Voice Assistant 🤖🗣️

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)

**Developer**: Cielo B. (cielo-b)  
**Email**: [irumvaregisdmc@gmail.com](mailto:irumvaregisdmc@gmail.com)  
**Course**: Intelligent Robotics  
**Instructor**: Gabriel Baziramwabo  
**Institution**: Rwanda Coding Academy  

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Detailed Functionality](#-detailed-functionality)
- [System Requirements](#-system-requirements)
- [Installation Guide](#-installation-guide)
- [Usage Instructions](#-usage-instructions)
- [Project Structure](#-project-structure)
- [Technical Stack](#-technical-stack)
- [License](#-license)
- [Contact](#-contact)

## 🌍 Project Overview

This Kinyarwanda Voice Assistant simulates how humanoid robots process voice interactions in local languages. The system:

1. **Listens** to Kinyarwanda speech (like robot ears)
2. **Understands** the question (like robot brain)
3. **Responds** with spoken answers (like robot mouth)

Developed for the Intelligent Robotics course, it demonstrates how robots can serve Rwandan communities in their native language.

## ✨ Key Features

| Feature | Technology Used | Purpose |
|---------|-----------------|---------|
| Speech-to-Text | KinyaWhisper (ASR) | Convert Kinyarwanda audio to text |
| Question Matching | NLP Dictionary | Map questions to correct answers |
| Text-to-Speech | gTTS | Generate Kinyarwanda voice responses |

## 🔍 Detailed Functionality

### 1. Speech Recognition (ASR)
- Uses KinyaWhisper (a Whisper model fine-tuned for Kinyarwanda)
- Processes audio files or microphone input
- Handles different audio formats (MP3, WAV)
- Outputs accurate Kinyarwanda transcriptions

### 2. Question Understanding (NLP)
- Pre-defined dictionary of 5+ QA pairs
- Exact matching algorithm (expandable to fuzzy matching)
- Returns "I don't know" for unmatched questions

### 3. Voice Response (TTS)
- Google's Text-to-Speech (gTTS) with Kinyarwanda support
- Generates clear, natural-sounding speech
- Saves responses as MP3 files
- Auto-plays responses in the interface

## 💻 System Requirements

- Operating System: Windows 10+, macOS 10.15+, or Linux
- Python: 3.8 or higher
- RAM: Minimum 4GB (8GB recommended)
- Disk Space: 2GB+ for models and dependencies
- Internet Connection: Required for first-time setup

## 📥 Installation Guide

### Step 1: Clone the Repository
```bash
git clone https://github.com/cielo-b/Kinyarwanda-Voice-Assistant.git
cd Kinyarwanda-Voice-Assistant
pip install -r requirements.txt