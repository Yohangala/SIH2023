# 🧠 CogniLearn — Cognitive Retraining Web App

> **Smart India Hackathon 2023** | Problem Statement: Cognitive Retraining for Children with Disabilities

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![SIH 2023](https://img.shields.io/badge/SIH-2023-orange?style=flat)](https://www.sih.gov.in/)

## 📌 Problem Statement

Children with cognitive and developmental disabilities often require structured, repetitive, and gamified learning to develop essential life skills. Traditional therapy methods lack interactivity and fail to sustain engagement. This project addresses the need for an accessible, browser-based cognitive retraining platform that allows children to practice core cognitive skills through guided interactive activities — no app installation needed.

## 🎯 Overview

CogniLearn is an interactive web application developed for **Smart India Hackathon 2023** that provides structured cognitive retraining exercises for children with disabilities. The platform covers six key cognitive domains — alphabet recognition, time-reading, emotional intelligence, shape recognition, memory, and daily life skills — all delivered through gamified, audio-visual feedback loops designed for therapeutic engagement.

## 🗂️ Learning Modules

| Module | Files | Description |
|--------|-------|-------------|
| 🔤 **ABC Learning** | `abcquiz.html` | Alphabet recognition with image associations and quiz |
| 🕐 **Clock Reading** | `clock.html`, `clockquiz.html` | Learn to read analog and digital clocks interactively |
| 😊 **Emotion Recognition** | `emoquiz.html`, `emotheory1-5.html` | 5-stage emotion theory lessons + recognition quiz using real facial images |
| 🔷 **Shapes Quiz** | `shapesquiz.html` | Visual shape identification (circle, square, triangle, star, oval, kite, rectangle, pentagon) |
| 🧠 **Memory Game** | `memory.html` | Card-matching memory game with audio feedback |
| 📖 **Story Module** | `story.html` | Guided storytelling for comprehension and sequence understanding |
| 🌞 **Daily Activities** | `dailyact.html` | Structured daily routine practice for life skills |
| ℹ️ **Information Pages** | `info1-3.html` | Onboarding and informational content for caregivers |

## 🎮 Gamification & Feedback

The platform uses multi-sensory feedback to reinforce learning:
- ✅ **Correct answer** → applause / fanfare audio (`clap.mp3`, `short-crowd-cheer.mp3`, `success-fanfare.mp3`)
- ❌ **Wrong answer** → gentle failure cue (`wah-wah-sad-trombone.mp3`)
- 🎵 **Background music** → 8-bit game music keeps sessions engaging
- 🖼️ **Visual emotion cues** → real facial expression images (happy, sad, angry, fear, surprised, shocked)

## 🗃️ Project Structure

```
SIH2023/
├── index.html              # Landing / home page
├── login.html              # User login
│
├── # Alphabet Module
├── abcquiz.html
├── a_learning.png, b_learning.png, c_learning.png, d_learning.png
│
├── # Clock Module
├── clock.html / clock.css / clock.js
├── clockquiz.html / clockquiz.css / clockquiz.js
│
├── # Emotion Module
├── emotheory1-5.html / emotheory.css   # 5 theory lessons
├── emoquiz.html / emoquiz.css / emoquiz.js
├── happy.png, sad.png, anger.png, fear.png, shock.png, surprised.jpg ...
│
├── # Shapes Module
├── shapesquiz.html
├── circle.png, square.png, triangle.png, star.jpeg, oval.jpeg ...
│
├── # Memory Game
├── memory.html / memory.css / memory.js
│
├── # Story & Daily Activities
├── story.html / story.css / story.js
├── dailyact.html / daily.css
│
├── # Shared & Info Pages
├── style.css               # Global styles
├── info1-3.html/css        # Caregiver info
├── login.css
│
└── # Audio Assets
    ├── clap.mp3, happy.mp3, sad.mp3, raju.mp3
    ├── short-crowd-cheer-6713.mp3
    ├── success-fanfare-trumpets-6185.mp3
    └── wah-wah-sad-trombone-6347.mp3
```

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (module-specific stylesheets) |
| Interactivity | Vanilla JavaScript |
| Media | MP3 audio, PNG/JPG/JPEG images |
| Deployment | Browser-based (no backend required) |

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Yohangala/SIH2023.git
   cd SIH2023
   ```

2. Open `index.html` in any modern browser — no server or dependencies needed.

3. Navigate through modules from the home screen.

> **Tip:** For the best experience with audio feedback, ensure your browser allows audio autoplay or interact with the page first.

## 🏆 Hackathon Context

- **Competition:** Smart India Hackathon (SIH) 2023
- **Problem Domain:** Health & Wellness / Education
- **Problem Statement:** Building a cognitive retraining tool for children with developmental and cognitive disabilities
- **Approach:** Browser-first design for maximum accessibility — works on any device with a modern browser, no app install required
- **Key Design Principles:** Repetition, gamification, multi-sensory feedback, simple UI for accessibility

## 👤 Author

**Yohan Gala**
B.Tech Computer Engineering, KJSIT Mumbai (2022–2026)

---
*Built with ❤️ for Smart India Hackathon 2023*
