# 😻 KittenTTS — Google Colab + Gradio UI

Run [KittenTTS](https://github.com/KittenML/KittenTTS) in your browser — no GPU, no setup, completely free.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/elkdev72/KittenTTS_Colab/blob/main/KittenTTS_Colab.ipynb)

---

## 🎬 Demo

> Watch the full tutorial on YouTube: **https://youtu.be/xidLnb8vwtk?si=zdTwt-NO7hJizaUy**

---

## ✨ What's Inside

A ready-to-run Colab notebook with a clean Gradio interface for KittenTTS — a state-of-the-art text-to-speech model that runs entirely on CPU.

**Features:**
- 🎙️ 8 built-in voices — Bella, Jasper, Luna, Bruno, Rosie, Hugo, Kiki, Leo
- 🤖 Choose from 4 models (25MB – 80MB)
- ⚡ Speed control (0.5× to 2.0×)
- 🔊 Instant audio playback + download
- 📚 Example texts to get started fast
- 🌐 Public shareable URL via Gradio

---

## 🚀 Quick Start

1. Click **Open in Colab** above
2. Run **Cell 1** — installs dependencies
3. Run **Cell 2** — loads the model manager
4. Run **Cell 3** — launches the Gradio UI
5. Click the public URL and start generating speech!

> First generation takes ~30 seconds to download model weights. After that it's fast.

---

## 🤖 Models

| Model | Params | Size | Speed |
|---|---|---|---|
| kitten-tts-mini | 80M | 80MB | Good |
| kitten-tts-micro | 40M | 41MB | Faster |
| kitten-tts-nano | 15M | 56MB | Fastest |
| kitten-tts-nano-int8 | 15M | **25MB** | Fastest |

> 💡 Start with **nano-int8** for the quickest experience.

---

## 🎙️ Voice Guide

| Voice | Style |
|---|---|
| Bella | Warm & friendly |
| Jasper | Clear & neutral |
| Luna | Soft & calm |
| Bruno | Deep & authoritative |
| Rosie | Bright & energetic |
| Hugo | Rich & resonant |
| Kiki | Young & cheerful |
| Leo | Smooth & professional |

---

## 📋 Requirements

- Google Account (for Colab)
- No GPU needed — runs on free CPU tier
- Python 3.12 (handled automatically in Colab)

---

## 🙏 Credits

- [KittenTTS](https://github.com/KittenML/KittenTTS) by KittenML / Stellon Labs
- [Gradio](https://gradio.app) for the UI
- Notebook by **elkdev72**

---

## 📄 License

This notebook is MIT licensed. KittenTTS itself is Apache-2.0 — see the [original repo](https://github.com/KittenML/KittenTTS) for details.
