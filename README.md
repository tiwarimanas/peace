# PEACE 🕊️
[Live Demo](https://tiwarimanas.github.io/peace/) | [Report Bug](https://github.com/tiwarimanas/peace/issues) 

PEACE is a completely browser-based, lightweight AI chat interface designed to bring advanced capabilities—like "forced thinking" and Claude-like "skills"—to smaller, natively incapable AI models.

## ✨ Features
* **🧠 Forced Thinking Routing:** Forces small models (like `gemini-2.5-flash-lite`) to analyze prompts, generate step-by-step plans, and feed them back to themselves to generate highly logical final responses.
* **🛠️ Custom "Skills":** Create custom AI personas tailored for highly specific tasks, similar to Claude's Projects.
* **📊 Inline Diagrams & Rich Media:** The AI can generate inline diagrams directly in the chat and supports GIF integration (requires your own Giphy API key).
* **🔒 100% Local & Private:** No backend databases. All your chat history, custom skills, and API keys are stored purely and securely in your browser's `localStorage`.

## 🚀 Getting Started
Because PEACE is currently running entirely in the browser, testing it is incredibly simple:
1. Clone the repository: `git clone https://github.com/tiwarimanas/peace.git`
2. Open the `index.html` file directly in your web browser.
3. Enter your Gemini API key in the settings panel.
4. Start chatting!

## 🤝 Contributing & The "Single File" Problem
I initially built PEACE as a fun, single-file HTML experiment. However, with all these advanced features, the codebase has grown massive. Ironically, the single file has become so large that AI context windows struggle to help me refactor or maintain it effectively!

**Our immediate goal is to refactor this single file into a modular, maintainable project.** If you are interested in prompt engineering, AI UI/UX, or want to help break this giant HTML file down into a modular React, Vue, or Vanilla JS project, your help would be incredibly appreciated! Please check out [`CONTRIBUTING.md`](CONTRIBUTING.md) to get started.

## 📜 License & Copyright
Copyright (c) 2026 Manas Tiwari.

This project is licensed under the GPL-3.0 License. You are free to use, modify, and distribute this software, but you must include the original copyright notice and attribute the original creator (Manas Tiwari). You may not claim this project as your own original work.
