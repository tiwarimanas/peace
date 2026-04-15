# PEACE 🕊️
[Live Demo](https://tiwarimanas.github.io/peace/) | [Report Bug](https://github.com/tiwarimanas/peace/issues) 

PEACE is a completely browser-based, lightweight AI chat interface designed to bring advanced capabilities—like "forced thinking" and Claude-like "skills"—to smaller, natively incapable AI models.

**⚠️ Important Note: PEACE is a "Bring Your Own Key" (BYOK) application. You must have a free Gemini API key to use the app. You will be prompted to enter it the moment you open the app.**

## ✨ Features
* **🔑 Bring Your Own Key:** Total control over your usage. PEACE requires you to enter your own Gemini API key to function, ensuring you aren't reliant on third-party rate limits.
* **🛡️ 100% Local & Private (Zero Server):** There is absolutely no backend server. Your API keys, chat history, generated plans, and custom skills **never leave your computer**. Everything is processed via direct API calls and saved purely in your browser's local storage.
* **🧠 Forced Thinking Routing:** Forces small models (like `gemini-2.5-flash-lite`) to analyze prompts, generate step-by-step plans, and feed them back to themselves to generate highly logical final responses.
* **🛠️ Custom "Skills":** Create custom AI personas tailored for highly specific tasks, similar to Claude's Projects.
* **📊 Inline Diagrams & Rich Media:** The AI can generate inline diagrams directly in the chat and supports GIF integration (requires a Giphy API key).

## 🚀 Getting Started
Because PEACE runs entirely on your local machine within the browser, setup is instantaneous:
1. Clone the repository: `git clone https://github.com/tiwarimanas/peace.git`
2. Open the `index.html` file directly in your web browser.
3. **Enter your Gemini API key** when the app prompts you on the startup screen.
4. Start chatting!

## 🤝 Contributing & The "Single File" Problem
I initially built PEACE as a fun, single-file HTML experiment. However, with all these advanced features, the codebase has grown massive. Ironically, the single file has become so large that AI context windows struggle to help me refactor or maintain it effectively!

**Our immediate goal is to refactor this single file into a modular, maintainable project.** If you are interested in prompt engineering, AI UI/UX, or want to help break this giant HTML file down into a modular React, Vue, or Vanilla JS project, your help would be incredibly appreciated! Please check out [`CONTRIBUTING.md`](CONTRIBUTING.md) to get started.

## 📜 License & Copyright
Copyright (c) 2026 Manas Tiwari.

This project is licensed under the GPL-3.0 License. You are free to use, modify, and distribute this software, but you must include the original copyright notice and attribute the original creator (Manas Tiwari). You may not claim this project as your own original work.
