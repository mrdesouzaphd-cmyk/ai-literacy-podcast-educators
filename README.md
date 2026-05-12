# 🎙️ AI Literacy Podcast for Educators

> **A science-based, quiz-style audio podcast helping educators build AI literacy — from general vocabulary to deep dives on LLMs like ChatGPT, Claude, Gemini, Grok, and Manus.**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![Audience: Educators](https://img.shields.io/badge/Audience-Educators-blue)
![Audio: Google AI Studio TTS](https://img.shields.io/badge/Audio-Google%20AI%20Studio%20TTS-orange)

---

## 🎯 Concept

Each episode follows a **quiz-style format**:

1. 🔊 **Question is asked** (with clear audio)
2. 🅐🅑🅒🅓 **Alternatives are read** one by one
3. ⏸️ **Pause moment** — listener thinks
4. ✅ **Correct answer is revealed** with a scientific explanation

All questions are **grounded in peer-reviewed science**, Dr. De Souza's research, and validated AI literacy frameworks.

---

## 📚 Course Structure

```
Module 1 — General AI Vocabulary      (Episodes 01–10)
Module 2 — How LLMs Work              (Episodes 11–20)
Module 3 — ChatGPT Deep Dive          (Episodes 21–28)
Module 4 — Claude AI Deep Dive        (Episodes 29–36)
Module 5 — Google Gemini Deep Dive    (Episodes 37–44)
Module 6 — Grok Deep Dive             (Episodes 45–52)
Module 7 — Manus AI Deep Dive         (Episodes 53–60)
Module 8 — AI in Education & Ethics   (Episodes 61–70)
```

---

## 🗂️ Repository Structure

```
ai-literacy-podcast-educators/
│
├── README.md                    ← You are here
├── player/
│   └── index.html               ← Web-based audio player (open in browser)
│
├── scripts/                     ← TTS-ready scripts for Google AI Studio
│   ├── module-01-general-ai/
│   │   ├── ep01-script.md
│   │   ├── ep02-script.md
│   │   └── ...
│   ├── module-02-llms/
│   ├── module-03-chatgpt/
│   ├── module-04-claude/
│   ├── module-05-gemini/
│   ├── module-06-grok/
│   ├── module-07-manus/
│   └── module-08-ethics/
│
├── audio/                       ← Downloaded .mp3/.wav files from Google AI Studio
│   ├── module-01-general-ai/
│   │   ├── ep01.mp3
│   │   └── ...
│   └── ...
│
├── transcripts/                 ← Full text transcripts per episode
│   └── ...
│
├── references/                  ← Scientific papers, Dr. De Souza's work
│   └── bibliography.md
│
└── CONTRIBUTING.md
```

---

## 🔧 How to Produce Audio (Free — No API Cost)

1. Open **[Google AI Studio → Generate Speech](https://aistudio.google.com/generate-speech)**
2. Copy a script from `/scripts/` into the text box
3. Select a voice (recommended: **"The Training Guide"** or **"The Patient Teacher"** template)
4. Click **Run** and listen
5. **Download** the audio file
6. Place it in the corresponding `/audio/module-XX/` folder
7. Commit to this repository

> ✅ **100% free** — Google AI Studio's Generate Speech runs in-browser with Gemini 3.1 Flash TTS Preview. No API key billing required for manual use.

---

## 🎤 Voice & Format Guidelines

| Element | Recommended Voice Style | Notes |
|---|---|---|
| Question narration | Calm, professional | Use "The Training Guide" preset |
| Alternatives A–D | Steady pace | One breath pause between each |
| Pause cue | Silence or gentle tone | Add 3–5 second gap in editing |
| Answer reveal | Warm, encouraging | Can use "The Patient Teacher" |
| Explanation | Clear, academic tone | Keep under 60 seconds |

---

## 📖 Scientific Grounding

All questions are based on:
- Dr. De Souza's peer-reviewed publications
- [Multidisciplinary AI — Substack](https://multidisciplinaryai.substack.com)
- OECD AI Principles, UNESCO AI Competency Frameworks
- Published benchmarks for LLM performance (MMLU, HumanEval, etc.)
- Cognitive load theory, adult learning theory (Knowles), and TPACK framework

See `/references/bibliography.md` for full citations.

---

## 🌐 Live Web Player

Open `player/index.html` in any browser to use the interactive quiz player.

---

## 📜 License

This project is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.
You may share and adapt with attribution to Dr. De Souza / DrDeSouzAI.

---

*Built by [DrDeSouzAI](https://github.com/mrdesouzaphd-cmyk) | Harvard GSE · PhD · AI Researcher & Educator*
