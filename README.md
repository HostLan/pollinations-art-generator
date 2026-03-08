# 🎨 AI Art Generator

**Version 2.0** — An AI-powered image generator web application using Pollinations.ai API.

## 🌟 Features

- 🎨 Generate images from text descriptions using AI
- 🎲 Random art generation
- 💡 Ready-to-use example prompts
- 📱 Responsive design
- ⚡ Fast and easy to use
- 🔄 Automatic retry logic (up to 3 attempts on failure)
- ⚠️ Inline error and warning messages (no blocking popups)
- ⏱️ 30-second timeout with automatic retry

## 🚀 Usage

1. Open `index.html` in your browser
2. Enter your image description
3. Click "Generate Image" button
4. See the AI-generated artwork!

## 💻 Technologies

- HTML5
- CSS3
- JavaScript (Vanilla)
- Pollinations.ai API

## 📋 Changelog

### v2.0
- Added automatic retry logic — retries up to 3 times on API failure or timeout
- Replaced blocking `alert()` dialogs with styled inline warning and error banners
- Added loading text that updates to reflect retry state (e.g. "Retrying... (attempt 2 of 3)")
- Added stale callback guard to prevent race conditions across retry cycles
- Added 30-second per-attempt timeout with automatic retry

### v1.0
- Initial release
- Basic image generation from text prompts
- Random prompt generation
- Example prompts panel

## 📝 License

MIT License - Feel free to use it!

## 🙏 Credits

- [Pollinations.ai](https://pollinations.ai) - For the free AI image generation API
