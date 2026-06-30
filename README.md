# 🚀 CodeMaker AI

CodeMaker AI is a premium, browser-based AI coding assistant that generates full-stack web applications from natural language prompts. Inspired by tools like Lovable and Base44, it features a sleek liquid-glass UI, a real-time agentic loop, and a built-in live preview engine.

Built entirely as a single-file HTML application, it runs anywhere without needing a backend server.

# ✨ Features

# 🧠 Agentic AI Loop

 Tool Calling: The AI uses a write_file tool to autonomously write code to the file system one file at a time, preventing context timeouts and truncated code.
 Multi-File Generation: Supports standard web files (index.html, style.css, script.js) as well as dynamic files like App.tsx, main.py, db.json, and design.md.
 Real-time Preview: Instantly renders generated HTML/CSS/JS in a sandboxed iframe.
# 🎨 Premium Design System

 Enforces strict UI/UX rules via a design.md file included in every project.
 Guarantees modern, sleek outputs with glassmorphism, CSS variables, and responsive layouts.
 Custom Skills: Users can add global rules (e.g., "Always use Tailwind", "Dark mode only") that the AI remembers across all projects.
# 📂 Project Management

 Version History: Automatically saves snapshots of your code before AI modifications. Rewind to any previous state instantly.
 File Locking: Lock specific files to prevent the AI from overwriting your manual edits.
 Prompt Enhancer: A built-in magic wand button expands simple ideas into highly detailed UI/UX prompts.
# 🖼️ Asset Generation

 Integrates with Agnes AI's native Image and Video models.
 Assets Tab: A dedicated workspace to preview, redo, edit, or accept generated media assets before applying them to the code.
# 📚 Verified Templates

 A library of 30 pre-configured templates (SaaS landing pages, games, portfolios, etc.).
 Features a Remix button that instantly imports the template's code and chat history into a new, editable project.
 Includes fully baked templates with real chat logs so users can see exactly how the AI was prompted.
# 🐙 GitHub Integration

 One-Click Export: Push your generated project directly to a new GitHub repository.
 Auto-README: The AI automatically analyzes your code and writes a professional README.md and commit message before pushing.
# 🛠️ Tech Stack

 Frontend: HTML5, CSS3 (Custom Liquid Glass UI), Vanilla JavaScript (ES6+)
 Styling: Tailwind CSS (CDN), Font Awesome
 Code Editor: CodeMirror 5
 AI Provider: Agnes AI (agnes-2.0-flash, agnes-video-v2.0, agnes-image-2.1-flash)
 Exporting: JSZip (ZIP downloads), GitHub REST API (Repo creation & Git Data API)
# 🚀 Getting Started

Download the Code: Save the HTML file to your local machine.
Open in Browser: Double-click the HTML file to open it in any modern browser (Chrome, Firefox, Safari, Edge).
Start Building:
 Type a prompt in the hero input box (e.g., "Build a pricing table with 3 tiers").
 Select an AI model (2.0 Flash is recommended for speed).
 Click Generate.
Interact:
 Use the chat panel to ask for modifications.
 Switch between Preview, Code, and Assets tabs.
 Lock files you want to keep safe, and use the History button to rewind if the AI makes a mistake.

# 🔑 Configuration

API Key

The app comes pre-configured with an Agnes AI API key. If you need to use your own, simply replace the API_KEY constant in the <script> section:

javascript

const API_KEY = 'your-agnes-ai-api-key';
GitHub Export

To use the GitHub export feature:

Click the GitHub icon (🐙) in the editor header.
Generate a Personal Access Token (PAT) in your GitHub Developer Settings with repo permissions.
Paste the token into the app. It will be saved securely in your browser's local storage for future use.

# 📄 License

This project is licensed under the MIT License - see the LICENSE file for details. (You can just use it however you want!)

<p align="center"> Built with ❤️ using Agnes AI </p>
