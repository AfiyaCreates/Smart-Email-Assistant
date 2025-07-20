# 📧 Smart Email Assistant

A personal project that combines **Spring Boot**, **Spring AI**, **Google's Gemini API**, and a **Chrome Extension** to create an AI-powered email reply assistant. The tool is designed to generate contextual, friendly, or professional email responses directly within Gmail, with both a web UI and browser extension integration.

---

## ✨ Features

- 🔐 Backend with Spring Boot and Spring AI
- 📡 Integration with Google Gemini API for intelligent email replies
- 💻 React-based frontend with Material UI
- 🧩 Chrome extension that detects Gmail DOM and injects smart replies
- 🧠 Clipboard copy functionality for generated content
- 🔍 Mutation Observer to track Gmail URL changes in real time
- 🌐 CORS-enabled APIs for cross-origin access

---

## 🧰 Tech Stack

| Layer        | Technologies                        |
|-------------|-------------------------------------|
| Backend      | Spring Boot, Spring AI              |
| AI Engine    | Google Gemini API                   |
| Frontend     | React, Material UI                  |
| Extension    | Chrome Extension (Manifest v3)      |
| Dev Tools    | IntelliJ, VS Code, Postman, Chrome DevTools |

---

## 🏗️ Architecture

User (Gmail) 
   ⬇️ (Extension)
Chrome Extension ———> Spring Boot API ———> Gemini API
        ⬆️                            ⬇️
     React UI (Optional)         AI-generated Reply

---

✨ Key Highlights

- 📬 AI-generated replies tailored for Gmail threads
- 🧠 Toggle between professional and friendly tones
- 🧩 Chrome Extension integrates seamlessly with Gmail
- ⚙️ Spring Boot + Spring AI backend with Gemini API
- 💻 Material UI-powered web interface
- 🔍 Mutation Observer tracks Gmail’s dynamic UI changes

---

🧠 What I Learned

- Building REST APIs and integrating external LLM APIs using Spring AI
- Managing cross-origin requests securely with CORS
- Structuring scalable full-stack applications
- Handling Gmail's dynamic DOM using JavaScript and MutationObserver
- Packaging and testing Chrome extensions

---

🚧 Future Enhancements

- 🔒 Add user authentication and role-based access
- 🗣️ Support more reply styles (casual, detailed, concise)
- ☁️ Deploy backend (Render) and frontend (Vercel)
- 📝 Add logging and error tracking
- 📜 Create reply templates and history management

---

🖼️ Screenshots

Gmail Integration	AI Reply Interface
<img width="799" height="620" alt="20 07 2025_18 41 41_REC" src="https://github.com/user-attachments/assets/5d6662d2-48ce-44a6-a0ca-c2c076022432" />
<img width="428" height="402" alt="20 07 2025_18 42 29_REC" src="https://github.com/user-attachments/assets/8ffd74f2-685b-42ad-a6bd-beb57437a18b" />

---

🙋‍♀️ About Me
Hi! I'm a developer passionate about building intelligent tools with real-world impact. This project helped me combine my interests in backend systems, AI, and web automation. I built it as a self-learning initiative to explore full-stack development with emerging AI technologies.

Feel free to explore, fork, or reach out for collaboration!
