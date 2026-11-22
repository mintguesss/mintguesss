<div align="center">

**English** · [中文](README.md)

# Ken Huang　黃予岑

**Computer Vision · Machine Learning · LLM Agent · Full-stack**

B.B.A. in Information Management, Fu Jen Catholic University · M.S. student in Information Management, National Central University (from 2026)<br>
Research —— multimodal fraud detection and real-time computer vision; training and tuning models<br>
Engineering —— PyTorch model deployment, verifiable LLM agents, Flask / Next.js full-stack

<br>

<a href="https://mintguesss.github.io/personal_web"><img src="https://img.shields.io/badge/Website-mintguesss.github.io-3B5BDB?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=1A1D23" height="46"></a>&nbsp;
<a href="https://mintguesss.github.io/repofolio/"><img src="https://img.shields.io/badge/Projects-Portfolio-3B5BDB?style=for-the-badge&logo=github&logoColor=white&labelColor=1A1D23" height="46"></a>

</div>

---

## 🛡️ [Fraud Radar](https://github.com/Liao-s-Research-Lab/fraud-radar)

A multimodal fraud detection platform. Paste text, a URL, or upload a screenshot, and within seconds it returns a fraud probability with a full analysis report.
The backend combines **BERT** semantic classification, **PaddleOCR** text extraction from screenshots, and headless-browser page crawling, cross-checked against the National Police Agency's published list of fraudulent websites.

> Extended into an NSTC undergraduate research project, *Improving Fraud Detection Accuracy with Integrated AI Techniques*: to address weak OCR output, **NLM denoising + Otsu thresholding** preprocessing combined with **CLIP zero-shot** semantic filtering improves the quality of BERT's input, raising AUC-ROC from **0.873 → 0.929**.

`PyTorch` `BERT` `PaddleOCR` `CLIP` `Flask` `Next.js` `React` `Firebase`

---

## 🎓 [Aidit — Academic Planning Agent](https://github.com/mintguesss/aidit)

A graduation-audit and course-planning agent that checks its sources and knows when to say "I don't know." [Live demo](https://aidit-weld.vercel.app)
In graduation audits, a wrong answer costs far more than no answer: credits are computed by a deterministic engine and the model only interprets intent. Where the rules are ambiguous, it doesn't guess — it flags the item for confirmation and tells you whom to ask.

- Credit calculation, scheduling, and source lookup never call the model, enforced by **dependency analysis in CI**
- Every conclusion cites the original regulation text; if the citation doesn't match, it's downgraded to "needs confirmation"
- **0 wrong answers** on a 35-case golden set; **10/10** on real transcripts, versus 9 of 20 when the same model calculates directly
- **100%** prompt-injection block rate with 0% false positives

`Next.js` `TypeScript` `Supabase` `Claude API` `LLM Agent`

---

## 👀 [Personal Assistant](https://github.com/mintguesss/personal-assistant)

Uses your laptop webcam to monitor posture, focus, emotion, and water intake in real time, with desktop notifications as reminders. Pure computer vision, runs locally, no wearables needed.

- **MediaPipe** —— pose / face landmarks to judge posture and presence
- **YOLOv11** —— hand-motion detection to recognize drinking
- **ViT** —— facial emotion classification
- All four models share a single real-time **OpenCV** pipeline

`MediaPipe` `YOLOv11` `ViT` `OpenCV` `Python`

---

## 📈 [Folio Manager](https://github.com/mintguesss/Folio-manager)

A personal finance and investment management web app, installable as a PWA.

- Realized P&L for both Taiwan and US stocks computed with **FIFO**
- US holdings store historical exchange rates to track TWD cost separately, avoiding distortion from converting at today's rate
- Expense tracking covers daily spending, travel abroad, and bill splitting with friends
- Background price sync is throttled dynamically according to market hours
- Multi-user data isolation via **Supabase RLS**

`Next.js` `TypeScript` `Supabase` `Tailwind CSS` `Vercel`

---

## Other Projects

| Project | What it does | Stack |
|---|---|---|
| 💰 [PromptMiser](https://github.com/mintguesss/PromptMiser) | Shows in real time how many tokens a piece of text costs across AI models and which is cheapest, then trims filler words to suggest savings | `Vue 3` `FastAPI` `tiktoken` |
| 🎙️ [nobook](https://github.com/mintguesss/nobook) | Live lecture transcription and notes: record on your phone, run ASR + LLM locally on your laptop, and have copy-ready notes before class ends — no cloud APIs | `faster-whisper` `llama.cpp` `FastAPI` |
| 📊 [ClaudeQuota](https://github.com/mintguesss/ClaudeQuota) | Windows tray utility showing your Claude subscription's 5-hour and weekly usage live | `Python` `Win32 API` |
| 🧹 [Clean-Contributors](https://github.com/mintguesss/Clean-Contributors) | Claude Code plugin that removes unwanted accounts from a GitHub repo's Contributors list | `Shell` `PowerShell` `GitHub API` |

---

<div align="center">

More projects & background → **[Website](https://mintguesss.github.io/personal_web)**

</div>
