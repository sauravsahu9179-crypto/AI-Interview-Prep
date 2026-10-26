# AI Interview Prep Dashboard 🎯

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-brightgreen?style=for-the-badge&logo=github)](https://sauravsahu9179-crypto.github.io/AI-Interview-Prep/)

🔗 **Live Application Link**: [https://sauravsahu9179-crypto.github.io/AI-Interview-Prep/](https://sauravsahu9179-crypto.github.io/AI-Interview-Prep/)

An intelligent, all-in-one interview preparation application powered by Google Gemini API. Built entirely with vanilla web technologies (HTML5, Tailwind CSS, ES Modules) and client-side storage—no Node.js, npm, or backend server required.

---

## ✨ Features

1. **Candidate Profile**
   - Save and persist your target role, current skills, weak areas, and target job description in browser `localStorage`.
2. **JD Analyzer**
   - Automatically parses job descriptions to extract required technical skills, soft skills, and core responsibilities.
3. **Match Score & Gap Analysis**
   - Evaluates profile competencies against the job description with a circular progress gauge, gap identification, and 3 actionable bridging steps.
4. **Question Generator**
   - Generates 5 tailored interview questions targeting your specific weak areas and job requirements across Technical, Behavioral, and System Design formats.
5. **Mock Evaluator (with Voice & STAR Method)**
   - **Guided STAR Mode**: Break down answers into Situation, Task, Action, and Result.
   - **Voice Input (STT)**: Dictate your answers using the browser's native Web Speech API.
   - **Audio Reader (TTS)**: Listen to questions read aloud with speech synthesis.
   - **Critique & Scoring**: Get an objective 0–10 score, rating level, identified strengths, and improvement suggestions.
6. **RAG Doubt Solver**
   - Interactive mentor chat for technical and conceptual questions with formatted code blocks and markdown rendering.
7. **Prep Plan Agent**
   - Custom 7-day sprint calendar with interactive, persistent checklists to keep your preparation on track.

---

## 🚀 Quick Start

### Option 1: Run Locally in Browser
1. Clone or download this repository.
2. Create a `.env` file in the root directory (refer to `.env.example`):
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```
3. Open `index.html` in your web browser or use a simple local server (such as VS Code Live Server).

### Option 2: Live on GitHub Pages
Because this application is a pure client-side single-page app, you can host it for free on **GitHub Pages**:
1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment**, set the Branch to `main` (or `master`) and folder to `/ (root)`.
3. Click **Save**. Your site will be live at `https://<username>.github.io/<repo-name>/`.

---

## 🔒 Security Note
- Never commit your private `.env` file or API keys to a public GitHub repository.
- A `.gitignore` file is included by default to prevent `.env` from being uploaded.

---

## 🛠️ Built With
- **HTML5 & Vanilla JavaScript (ESM)**
- **Tailwind CSS** (CDN)
- **Lucide Icons**
- **Marked.js** (Markdown parsing)
- **Google Generative AI SDK** (`@google/generative-ai` via ESM)
