# 🖼️ AVIF Viewer

> Fast, privacy-first AVIF image viewer that runs entirely in your browser

[![Live Demo](https://img.shields.io/badge/demo-avif.pics-blue)](https://avif.pics)
[![HuggingFace](https://img.shields.io/badge/🤗-HuggingFace%20Space-yellow)](https://huggingface.co/spaces/YOUR_USERNAME/avif-viewer)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## 🎯 What is this?

A browser-based AVIF image viewer that solves a simple problem: opening `.avif` files without installing sketchy third-party software.

AVIF is a modern image format with excellent compression, but native OS support is inconsistent. This tool works everywhere, instantly.

**Try it now:** [avif.pics](https://avif.pics)

## ✨ Features

- **🔒 Privacy-first** - All processing happens client-side, your files never leave your device
- **📦 Zero installs** - Works in any modern browser
- **🌍 Cross-platform** - Windows, Mac, Linux, iOS, Android
- **⚡ Instant** - No uploads, no waiting
- **🛡️ Better error handling** - Handles corrupted AVIF files better than native viewers
- **🎨 Simple UI** - Just drag, drop, view

## 🚀 Why I Built This

Downloaded an AVIF file. Couldn't open it. Didn't want to install random software. Built this instead.

## 🛠️ Tech Stack

- Pure JavaScript (no frameworks)
- HTML5 Canvas API
- Client-side file processing
- No backend, no database, no tracking

## 💻 Local Development

Want to run it locally or contribute?
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/avif-viewer.git
cd avif-viewer

# Open in browser (no build step needed!)
open index.html
# or use a local server:
python -m http.server 8000
```

That's it. No dependencies, no npm install, no build process.

## 📖 How It Works

1. User selects/drops an AVIF file
2. File is read using FileReader API (client-side)
3. Rendered to HTML5 Canvas
4. Displayed in browser

**Your file never touches a server.** Everything happens in your browser's memory.

## 🤝 Contributing

Found a bug? Have an idea? PRs welcome!

Some ideas for improvements:
- Batch viewing multiple files
- Basic editing tools (crop, resize)
- Export to other formats (PNG/JPEG)
- Drag-and-drop gallery view

## 📝 License

MIT - Free to use, modify, and distribute.

## 🔗 Links

- **Live Tool**: [avif.pics](https://avif.pics)
- **HuggingFace Space**: [View on HuggingFace](https://huggingface.co/spaces/YOUR_USERNAME/avif-viewer)
- **Indie Hackers**: [Read the story](https://www.indiehackers.com)

## 🙏 Support

If you find this useful:
- ⭐ Star this repo
- 🐦 [Share on Twitter](https://twitter.com/intent/tweet?text=Check%20out%20avif.pics%20-%20a%20browser-based%20AVIF%20viewer!%20https://avif.pics)
- 🐛 Report bugs via Issues

---

Built by an indie developer who needed a simple solution to an annoying problem.

**No tracking. No ads. No BS. Just a tool that works.**
