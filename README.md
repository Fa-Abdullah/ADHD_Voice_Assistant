# ADHD Smart Assistant 

An AI-powered voice assistant designed to support children with ADHD through emotion detection, personalized exercises, and a reward system.

## Overview

Kawkaby is a smart assistant that helps children with ADHD by:
- Analyzing emotional state from speech or text
- Providing personalized exercises based on detected emotions
- Offering encouragement through a gamified reward system
- Supporting both voice and text input with Arabic/English language options

## Features

- **Speech-to-Text**: Uses OpenAI Whisper for accurate transcription
- **Emotion Detection**: Identifies emotions (happy, stressed, distracted, bored)
- **Personalized Exercises**: Suggests activities based on emotional state
- **Reward System**: Points-based gamification to encourage engagement
- **Text-to-Speech**: Converts responses to speech using gTTS
- **Multi-language**: Supports Arabic and English
- **Personality Options**: Funny or Calm assistant personality

## Technologies

| Component | Technology |
|-----------|-----------|
| LLM | OpenRouter (GPT-4o-mini) |
| STT | OpenAI Whisper |
| TTS | gTTS |
| Framework | LangChain |
| UI | Gradio |
| Language | Python |

## How It Works

User inputs text or speaks via microphone
Whisper converts speech to text (if using voice)
LLM analyzes emotion from the text
System generates a personalized exercise
Reward points are updated
Response is converted to speech (if in voice mode)
All displayed in Gradio interface

