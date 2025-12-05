# shdai – Offline AI Chatbot on Android (Text & Voice)

Welcome! This guide helps you set up a fully offline, privacy-respecting AI chatbot on your Android phone—no server, no computer, no cloud required. You’ll use open-source apps to run a small Llama or similar AI model with both text typing and voice input.

---

## 📱 What You Need

- **An Android phone** (preferably with at least 3GB RAM for best results)
- **A supported AI chatbot app** (see below)
- **A quantized AI model file** (see model guide)
- (Optional) **Google Speech Recognition** for voice-to-text input

---

## 🚀 Quick Start

### 1. Pick & Install an Open-Source AI Chat App

We recommend:
- [MLC Chat (Android)](https://mlc.ai/mlc-chat/)
- [LM Studio (future Android support)](https://lmstudio.ai/) *(Experimental)*
- [LiteLLM Android (F-Droid/Apk)](https://github.com/jmorganca/ollama-android) *(Experimental)*

See [`app_sources.md`](app_sources.md) for more.

> **Install via Play Store if available, or download the APK from the official releases if not.  
> Enable “install from unknown sources” if prompted.**

---

### 2. Download a Small Quantized AI Model

- We recommend:  
  - **TinyLlama 1.1B** (super lightweight, good for basic chat)  
  - **Phi-2, Alpaca 1.3B, or similar** (see [setup_android_model.md](setup_android_model.md) for links & details)

- Download the `.gguf` or `.bin` file to your phone (often via browser or file transfer).
- Place the model in your app’s “models” folder, or follow the in-app import step.

---

### 3. Configure the App

1. Open your installed AI chat app.
2. In “Model” or “Import Model”, select the downloaded model file.
3. Adjust settings—make sure quantized (Q4 or Q8) is chosen for best performance.

---

### 4. Chatting (Text & Voice)

- **Text:** Type into the chat box as usual.
- **Voice:** Look for a small microphone icon; tap it to dictate your question (requires speech recognition permissions).
  - Some apps use Google Speech built-in, others use Android’s own module.

---

### 🔥 Tips and FAQ

- The smaller the model, the faster it runs—but conversation quality may be limited.
- Need more languages? Check model/app options.
- Trouble with installations? See [Troubleshooting](#troubleshooting).
- Want an app not listed? See [app_sources.md](app_sources.md).

---

## 🛠 Troubleshooting

- **App won’t open/installs fail:** You may need to allow installation from unknown sources in Android settings.
- **Model not recognized:** Wrong format—use `.gguf` or `.bin` as supported by your app.
- **No voice button:** Not all apps support voice by default; see [app_sources.md](app_sources.md) for feature list.

---

## 📝 Credits & Licensing

- Project lead: [theoneethicalhacker](https://github.com/theoneethicalhacker)
- This guide is 100% open and free to adapt!

---
