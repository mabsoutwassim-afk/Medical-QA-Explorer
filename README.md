# Medical QA Explorer 🩺

An interactive, responsive web application for exploring and testing medical knowledge using the Hugging Face `Starlord1010/Medical-QA-dataset`.

## 🚀 Features

- **⚡ Quiz & Self-Assessment Mode**:
  - Timed medical questions with customizable countdown durations (15s, 30s, 45s, 60s, or Off).
  - Draft answer area to practice typing your answer before revealing the official response.
  - Interactive self-rating ("Got It Right", "Needs Review") to track score, accuracy rate, and active streaks.

- **🌙 Dark / Light Mode**:
  - Seamless toggle between dark and light themes with preference saved in `localStorage`.

- **⭐ Saved Questions / Bookmarks**:
  - Bookmark tricky questions with a single click or keyboard shortcut.
  - Review saved questions anytime in the dedicated **Saved** tab.

- **🔍 Browse & Search**:
  - Real-time keyword search across all medical questions and responses in the dataset.
  - Jump directly to any specific question in Quiz mode.

- **🔊 Text-to-Speech & Copy**:
  - Read questions and answers aloud using the Web Speech API.
  - One-click copy buttons for questions and answers.

- **⌨️ Keyboard Shortcuts**:
  - <kbd>Space</kbd>: Reveal answer / Load next question
  - <kbd>B</kbd>: Bookmark current question
  - <kbd>S</kbd>: Speak / Read question aloud

- **💾 Persistent State**:
  - Progress stats, bookmarks, theme preference, and timer settings automatically persist in `localStorage`.

## 🛠️ Usage

1. Open `index.html` directly in any web browser or serve via a local HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
2. Navigate to `http://localhost:8000` in your web browser.

## 📊 Dataset

Dataset source: [Starlord1010/Medical-QA-dataset on Hugging Face](https://huggingface.co/datasets/Starlord1010/Medical-QA-dataset).
