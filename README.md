# 🎥 Text to Video Generator 

> A powerful AI-driven pipeline that transforms raw textual prompts into educational or explanatory videos using the [Manim](https://www.manim.community/) animation engine and the OpenAI GPT API.

---

## 🚀 Project Overview

This project automates the generation of concept-based explainer videos using the **Manim Community Library**, powered by **OpenAI GPT** for script and animation logic, and optional **TTS (Text-to-Speech)** narration.

### 🔄 Pipeline Flow:

1. **Input Prompt**: User provides a raw topic or concept.
2. **Script Generation**: GPT-4 generates narration and scene breakdowns.
3. **Manim Code Generation**: GPT writes scene-specific Manim Python code.
4. **Animation Rendering**: Manim renders visual scenes.
5. **Optional TTS**: Text narration is converted into audio.
6. **Video Compilation**: Video and audio are merged into a final video output.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Backend scripting |
| **OpenAI GPT-4/GPT-4o API** | Prompt enhancement & code generation |
| **Manim Community Edition** | Mathematical animations |
| **gTTS / Tortoise TTS / ElevenLabs** | Optional voice-over generation |
| **MoviePy** | Video/audio stitching |
| **Tesseract OCR (optional)** | Extract text from video frames |

---


## 📌 Features
🎙️ Natural narration generation

📽️ Animated scenes via Manim

🧠 GPT-based automatic scene coding

🔄 End-to-end pipeline: prompt → video

🔊 Optional TTS voice-over integration


## 🧩 Future Improvements
Add GUI using Streamlit or Gradio

Multi-language narration support

Visual template selection

Subtitle generation and embedding


## 🙋‍♂️ Acknowledgments
Manim Community

OpenAI

gTTS

MoviePy
