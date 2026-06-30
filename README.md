# Mothusi — The Student Voice and Chatbot Assistant. Built in Botswana. For Computer Studies Students.

## Download
**[⬇ Download Mothusi V3.1 (.exe)](https://drive.google.com/file/d/1D-A1PlmwMFwzrenTpy5idwbM1ehSBrcZ/view?usp=drivesdk)**

Windows only. No Python required. Double-click and run.

---

## What is Mothusi?
Mothusi is a BGCSE Computer Studies AI study assistant built for Computer Studies Students. Students can ask questions, take AI-generated quizzes, and get instant answers — using voice or text — without needing a teacher present.

*Mothusi* means "helper" in Setswana.

---

## What's New in V3.1
Five bugs fixed from V3.0:
- Fixed crash on quiz completion (score_text.append error)
- Fixed quiz answers going to chat instead of quiz mode
- Fixed Groq printing its own name in responses
- Fixed session save missing required arguments
- Fixed function name mismatch causing save failures

Also updated the syllabus with weak topics flagged in the 2024 BGCSE examiner report — including verification vs validation, COUNTIF/IF formulas, specialised input devices, and NIC/HUB functions.

---

## Features
- Google AI-style GUI — white and blue, clean and professional
- Student login system with unique generated codes (e.g. AMMP for Amantle Mpaekae)
- AI answers scoped strictly to the BGCSE Computer Studies syllabus
- Quiz mode — 7 questions, 10 marks, 2 attempts per question, wrong answer review
- Dual input — type or speak, both work the same way
- Natural voice responses using Microsoft edge-tts AriaNeural
- Session auto-save on close
- Sidebar showing recent question topics
- Offline fallback message when no internet connection

---

## How to Use
1. Download the .exe from the link above
2. Get a free Groq API key from [console.groq.com](https://console.groq.com)
3. Create a `.env` file next to the .exe: `GROQ_API_KEY=your_key_here`
4. Double-click `mothusiv3.exe` to run
5. Register with your name or log in with your student code

---

## Built With
- Python
- tkinter (GUI)
- Groq AI — llama-3.1-8b-instant
- edge-tts — AriaNeural voice
- SpeechRecognition + PyAudio
- PyInstaller (packaging)

---

## Requirements
- Windows 10 or 11
- Internet connection (required for AI responses)
- Microphone (optional — text input works without one)

---

## Versions
| Version | Description |
|---------|-------------|
| V3.1 | Bug fixes — quiz input routing, name printing, session save logic. Updated syllabus with 2024 examiner report weak topics. |
| V3.0 | Full GUI rebuild — login system, quiz mode, dual input, edge-tts voice |
| V2.0 | Added student records, testme(), GUI interface |
| V1.0 | First release — voice commands, AI answers, terminal interface |

---

## Roadmap
- **July 2026** — Build web landing page (CSS)
- **August 2026** — JavaScript and Fetch API integration
- **September 2026** — Flask backend, Mothusi runs in browser
- **November 2026** — Migrate student data to Supabase
- **December 2026** — Launch at mothusi.study

---

## Developer
**Mulax Prime** (Amantle Mpaekae) | Mogoditshane, Botswana

[GitHub](https://github.com/mulaxprime) · [Portfolio](https://mulaxprime.github.io)
