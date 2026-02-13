# Jimeng Async UI 🎨

A standalone Windows 98/2000 style web UI for the `jimeng-api` asynchronous task system.

## ✨ Features
- **Retro Aesthetic**: Meticulously designed using `98.css` to emulate the classic Windows 2000 look and feel.
- **Pure Frontend**: A single `index.html` file with no build step required. Uses Vue 3 and Axios via CDN.
- **Zero Configuration DB**: Leverages browser `localStorage` for configuration and task history persistence, and `IndexedDB` for offline media caching.
- **Instant Media Preview**: Generated images and videos are cached locally. No more broken CDN links when reviewing past generations!
- **Auto Polling**: Automatically polls the backend for task status with adjustable intervals.
- **Credit Tracking**: Real-time display of your account point balance across multiple tokens.

## 🚀 Usage

Since it's a single HTML file with no external dependencies other than CDNs, you can use it in several ways:

1. **Directly open `index.html`** in your browser.
2. **Host it anywhere**: Vercel, GitHub Pages, Cloudflare Pages, or even a simple Python HTTP server.

*Note: You need to set the API Base URL and Session ID (from your `jimeng-api` instance) in the "Configuration.exe" window before submitting tasks.*

## 📸 Screenshots
*(Add screenshots of the UI here)*

## 🛠️ Built With
- [Vue 3](https://vuejs.org/)
- [Axios](https://axios-http.com/)
- [98.css](https://jdan.github.io/98.css/)

## 📝 License
MIT License
