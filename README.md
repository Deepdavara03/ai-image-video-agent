# Ai-image-video-agent
# 🤖 AI Image & Video Generation Agent

An AI-powered **Telegram media generation agent built with n8n** that allows users to generate AI images and videos using natural-language prompts.

The agent understands user intent, creates optimized prompts, routes requests to the appropriate image or video generation pipeline, waits for asynchronous generation, generates captions, and delivers the final media directly through Telegram.

---

## 🚀 Features

- 🤖 AI-powered conversational agent
- 🖼️ AI image generation
- 🎥 AI video generation
- 💬 Telegram-based user interface
- 🧠 Automatic intent detection
- ✨ AI prompt enhancement
- 🔀 Automatic image/video routing
- ⏳ Handles asynchronous generation and waiting
- 📝 Automatic caption generation
- 📤 Sends generated media directly to Telegram
- 🔎 Web-based knowledge/query support
- 💾 Conversational memory

---

## 🧠 How It Works

```text
Telegram User
      ↓
Telegram Trigger
      ↓
Understand User Intent
      ↓
 ┌───────────────┐
 │ Image / Video │
 │ / General     │
 │ Query         │
 └───────┬───────┘
         ↓
   AI Prompt Agent
         ↓
   Detect Media Type
      ↙       ↘
   Image      Video
     ↓          ↓
Image Engine  Video Engine
     ↓          ↓
   Wait / Check Generation
         ↓
   Generate Caption
         ↓
 Send Media to Telegram
