# 🦖 Dinosaur Master

Dinosaur Master is an AI-powered YouTube automation system that generates and uploads cinematic dinosaur videos automatically.

This project uses N8N for workflow orchestration and Python for video rendering, combined with AI APIs for script generation, image creation, and voice synthesis.

---

## 🚀 Project Goal

To build a semi-automated AI content pipeline that:

- Generates viral dinosaur video ideas
- Creates cinematic scripts using AI
- Generates realistic AI dinosaur images
- Produces AI voice narration
- Combines everything into a final video
- Uploads automatically to YouTube

Initial Phase:
- 2 videos per week
- Focus on quality
- Gradually scale to daily uploads

---

## 🏗️ System Architecture

CRON Trigger (N8N)
↓
Topic Input / Trend Detection
↓
OpenAI - Script Generation
↓
Image Generation API
↓
Voice Generation API
↓
Python Video Builder (FFmpeg)
↓
YouTube Upload API


---

## 🛠️ Tech Stack

### Automation
- N8N

### Backend
- Python 3.x
- FFmpeg

### AI Services
- OpenAI API (Script generation)
- Leonardo AI / Pika (Image generation)
- ElevenLabs (Voice synthesis)

### Distribution
- YouTube Data API v3

---

## 📂 Project Structure

dinosaur-master/
│
├── n8n-workflow/
│ └── workflow.json
│
├── video-builder/
│ ├── main.py
│ ├── assets/
│ │ ├── background_music.mp3
│ │ └── font.ttf
│ └── output/
│ └── final.mp4
│
├── .env
├── requirements.txt
└── README.md


---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/dinosaur-master.git
cd dinosaur-master

pip install -r requirements.txt
