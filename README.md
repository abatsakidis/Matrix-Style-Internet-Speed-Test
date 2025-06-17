# 💻 Matrix-Style Internet Speed Test (HTML + JavaScript)

This is a minimal, hacking-themed Internet speed test tool with a retro "Matrix-style" UI. It supports both dark and light modes, and is fully responsive for mobile and desktop users.

## 🚀 Features

- ✅ Internet speed test: **Download**, **Upload**, and **Ping**
- 🧪 Uses real-time browser performance APIs (no dependencies)
- 🌙 **Dark/Light mode toggle**
- 🎥 **Matrix-style animation** in background (only in dark mode)
- 📱 Mobile-friendly UI
- 💡 No external libraries required

## 📸 Screenshot

![screenshot](screenshot.png)

## 🛠️ How to Use

1. Clone or download the repository.
2. Open `index.html` in your browser.
3. Click the `▶ Run All Tests` button.
4. Toggle between Dark/Light mode using the `🌓` button.

> This project runs 100% client-side. It does not collect or transmit any data to a server.

## 📦 Files

| File         | Description                          |
|--------------|--------------------------------------|
| `index.html` | Main HTML + JavaScript code          |
| `README.md`  | This documentation file              |

## 🧠 Technical Notes

- **Download test** uses a 10MB fetch from Cloudflare.
- **Upload test** uses `httpbin.org/post` with a 5MB binary payload.
- **Ping test** performs multiple fetches to measure average latency and jitter.
- The matrix animation is implemented with a `<canvas>` overlay.

## ⚠️ Limitations

- Upload and download speeds may vary depending on CORS and network limitations.
- Not a substitute for dedicated tools like Speedtest.net or fast.com.

## 📄 License

MIT License

---

> Inspired by the aesthetics of retro hacking terminals and the Matrix universe.
