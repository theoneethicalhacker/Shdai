# Guide: Downloading and Importing a Quantized Model on Android

## 1. Recommended Models

- **TinyLlama 1.1B**  
  - HuggingFace: https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0-GGUF  
  - Choose a quantized `.gguf` file like `q4_K_M.gguf` or `q8_0.gguf`

- **Phi-2 (Lite-7B/2.7B)**  
  - HuggingFace: https://huggingface.co/microsoft/phi-2  
  - Look for any models labeled `ggml` or `gguf` (smaller is faster!)

- **Alpaca 1.3B (q4)**  
  - HuggingFace: https://huggingface.co/Samurai/alpaca-1.3B-GGML

## 2. Download

- Open the Hugging Face page above via your Android browser.
- Scroll down to “Files and versions.”
- Download the desired `.gguf` or `.bin` file directly to your phone’s Downloads folder.

## 3. Import into Your App

- Open your AI chat app (e.g., MLC Chat).
- Go to **Model Import** or **Load Model**.
- Browse to the file and select it.
- Wait for the model to load. For a first load, it may take up to a minute.

## 4. Running the Model

- Once loaded, just start chatting!
- If the app asks for quantization level, pick “Q4” for best blend of speed and quality.
- **If ‘low memory’ errors appear, use a smaller/extra-quantized model.**

## 💡 Troubleshooting

- **Model format error:** Only `.gguf` or `.bin` supported (depends on app—see [app_sources.md](app_sources.md)).
- **Slow or crashing:** Try an even smaller model file.

---