# SD-IMG: PixelForge Pro AI Image Assistant 🖌️🖼️

A professional AI image assistant and prompt builder for Stable Diffusion.

## 🚀 Features
- **Layers System**: Build complex prompts using multiple layers.
- **Model Management**: Keep track of your favorite SD models.
- **Mobile Optimized**: Access your AI studio from your phone.
- **Zero-Click Clipboard Sync**: Sync prompts between your PC and mobile device.
- **CORS Proxy**: Foolproof connection to any Stable Diffusion API.

## 📥 Access the Apps
Choose the version you want to use:

### 1. 🎨 [**AI Studio Pro (Mobile Optimized)**](https://milak-web.github.io/SD-IMG/ai%20img.html)
*The normal "AI Image" app you use for generation.*

### 2. 🎙️ [**PixelForge Pro (Assistant)**](https://milak-web.github.io/SD-IMG/AI%20Studio%20Pro.html)
*The lightweight assistant version.*

---

## 🚀 How to Fix "PROXY OFFLINE" (IMPORTANT)
If you are browsing from **GitHub (HTTPS)**, your browser will block the connection to your **Local PC (HTTP)** for security.

To fix this and get a smooth experience:
1. Run `python cors_proxy.py` on your PC.
2. Open the **Local Address** provided in the terminal:
   👉 [**http://127.0.0.1:8001**](http://127.0.0.1:8001)

This bypasses the browser block and works perfectly.

---

## 🛠️ Requirements
- Python 3.x
- `flask`, `flask-cors`, `pyperclip`, `requests`

```bash
pip install flask flask-cors pyperclip requests
```

## 📜 License
MIT License
