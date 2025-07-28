# 🎬 YouTube Shorts Automation Workflow using n8n

This project is a fully automated content creation pipeline that generates and uploads **YouTube Shorts** using AI, open APIs, and the powerful workflow automation tool **n8n**.

> 🚀 Build short-form videos in seconds — from topic input to YouTube upload — with zero manual editing!

---

## 💻![AgenturlebenAgencylifeGIF](https://github.com/user-attachments/assets/14599d4c-ebab-4db6-983c-dbba0c374e76)


**<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/342a4501-e6c1-43c6-a51d-7a1e611df2d3" />
**


## 📌 Features

- 🔮 **AI Script Generation** using [OpenRouter](https://openrouter.ai) (DeepSeek LLaMA 70B)
- 🎞️ **Scene-based Background Video Search** using [Pexels API](https://www.pexels.com/api/)
- 🎧 **AI-based Music Tag Selector** based on video mood
- 📦 **Video Generation API** to stitch clips, voice, and background music
- ⏳ **Async Video Rendering Polling** until completion
- 📤 **Automated Upload to YouTube Shorts** using the YouTube Data API v3
- 📁 **Modular and Configurable Workflow** via n8n

---

## 🛠️ Tech Stack

| Tool            | Purpose                                    |
|-----------------|--------------------------------------------|
| `n8n`           | Automation and workflow orchestration      |
| `OpenRouter`    | AI content generation (DeepSeek LLaMA 70B) |
| `LangChain`     | Prompt parsing and structured outputs       |
| `Pexels API`    | Free stock video search                    |
| `Custom Node.js API` | Video composition (TTS + video editing)   |
| `YouTube API`   | Programmatic Shorts upload                 |

---

## ⚙️ How It Works

1. **Input Topic** → Enter a video topic (e.g. “space facts”)
2. **AI generates 2 scenes** → Text and search terms using LLM
3. **Pexels API** fetches background videos
4. **Music Selector** chooses suitable background music
5. **TTS & Video Generator API** composes the video
6. **Video Status is polled** until it's ready
7. **YouTube API** uploads the completed video as a Short

---

## 📸 Screenshots

| AI Prompting | Scene Output | Pexels Video | Final Upload |
|--------------|---------------|----------------|----------------|
| ![ai](docs/ai.png) | ![scene](docs/scene.png) | ![pexels](docs/pexels.png) | ![yt](docs/youtube.png) |

---


