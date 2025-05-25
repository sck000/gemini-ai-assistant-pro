# 🤖 Gemini AI Assistant Pro

[![Version](https://img.shields.io/badge/version-2.6.0-blue.svg)](https://github.com/Sck000/gemini-ai-assistant-pro/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-orange.svg)](https://developer.chrome.com/docs/extensions/)
[![Manifest V3](https://img.shields.io/badge/Manifest-V3-purple.svg)](https://developer.chrome.com/docs/extensions/mv3/intro/)

> **Complete AI assistant with Gemini: analyze pages, improve texts, translate content and much more - Works without API key!**

## ✨ What This Extension Does

Transform your browsing experience with AI-powered assistance:

- 📄 **Summarize any webpage** with one click
- ✍️ **Improve and rewrite text** (make it formal/casual, fix grammar)
- 🌍 **Translate selected text** instantly
- 🔍 **Analyze page content** and fact-check information
- 💡 **Answer questions** about what you're reading
- 🎯 **Quick actions** via right-click context menu
- ⌨️ **Keyboard shortcuts** (Ctrl+Shift+G to open)

## 🆓 Works Without API Key!

**Three modes available:**
1. **🤖 Gemini Nano (Offline)** - 100% private, works without internet
2. **🌐 Web Mode** - Uses gemini.google.com directly, no API needed
3. **🔑 API Mode** - For advanced users with their own API key

## 🚀 Quick Start

### Installation
1. Download the latest release from [Releases](https://github.com/Sck000/gemini-ai-assistant-pro/releases)
2. Extract the ZIP file
3. Open Chrome and go to `chrome://extensions/`
4. Enable "Developer mode" (top right)
5. Click "Load unpacked" and select the extracted folder

### Usage
- **Right-click** on any text → Select AI action
- **Ctrl+Shift+G** (Cmd+Shift+G on Mac) → Open assistant
- **Click extension icon** → Access full interface

## 🌍 Supported Languages

- 🇺🇸 English
- 🇮🇹 Italian  
- 🇪🇸 Spanish
- 🇫🇷 French
- 🇩🇪 German

## 🛠️ For Developers

### Project Structure
```
gemini-ai-assistant-pro/
├── manifest.json          # Extension manifest
├── popup/                 # Main interface
├── background/            # Service worker
├── content/               # Content scripts
├── options/               # Settings page
├── _locales/             # Internationalization
└── assets/               # Icons and resources
```

### Build & Development
```bash
npm install
npm run build
npm run validate
```

## 🤝 Contributing

**I'm not a professional developer** - this extension works but could definitely be improved! 

Looking for help with:
- 🐛 Bug fixes
- ✨ New features
- 🎨 UI improvements
- 🔧 Code optimization
- 📚 Better documentation

### How to Contribute
1. Fork this repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📋 Features Overview

### ⚡ Quick Assistant
- Instant answers to any question
- Page summarization
- Content explanation

### ✍️ Writing Tools
- Text improvement and correction
- Style transformation (formal ↔ casual)
- Grammar and syntax fixes

### 🔍 Research Tools
- Page analysis and fact-checking
- Information extraction
- Contextual research

## 🔒 Privacy & Security

- ✅ **Minimal permissions** - only what's necessary
- ✅ **No data collection** - everything stays local
- ✅ **Open source** - you can see exactly what it does
- ✅ **Offline mode available** - works without sending data anywhere

## 📊 Technical Details

- **Manifest Version:** V3 (latest Chrome standard)
- **Permissions:** activeTab, contextMenus, storage, scripting, notifications
- **Supported Models:** Gemini Nano, Gemini 2.5 Pro, Gemini 2.5 Flash
- **Build System:** Node.js with validation scripts

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Google for the amazing Gemini AI models
- Chrome Extensions team for the excellent documentation
- The open source community for inspiration and tools

## 📞 Support

- 🐛 **Bug Reports:** [Open an issue](https://github.com/Sck000/gemini-ai-assistant-pro/issues)
- 💡 **Feature Requests:** [Start a discussion](https://github.com/Sck000/gemini-ai-assistant-pro/discussions)
- 📚 **Documentation:** Check the [docs](docs/) folder

---

**Made with ❤️ by someone who's still learning to code properly!**

*If you find this useful, please consider giving it a ⭐ and helping improve it!* 
