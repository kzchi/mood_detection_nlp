# Cantonese Mood Detection

A Python-based tool that uses the Whisper-small-cantonese model to detect mood from Cantonese audio input.

## Description

This project uses the `alvanlii/whisper-small-cantonese` model to transcribe Cantonese speech and analyze the emotional content of the speech. It can detect various moods including:
- 開心 (Happy)
- 嬲 (Angry)
- 傷心 (Sad)
- 平靜 (Neutral)

## Prerequisites

Make sure you have Python installed and the following libraries:
```bash
pip install librosa transformers torch
