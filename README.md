<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=36&pause=1000&color=36BCF7&center=true&vCenter=true&width=900&lines=Quiz+App+Master;A+Modern+Developer-Friendly+Quiz+Engine" alt="Typewriter Heading" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/Made%20with-JavaScript-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/PWA-ready-blueviolet" />
  <img src="https://img.shields.io/badge/Auth-Google%2FGitHub-green" />
  <img src="https://img.shields.io/badge/Leaderboard-Global%2FLocal-orange" />
  <img src="https://img.shields.io/github/actions/workflow/status/<user>/<repo>/ci.yml?label=CI%2FCD" />
</p>

---

> **Quiz App Master** is a modern, hackable quiz engine designed for developers, educators, and tinkerers.  
> Build, customize, and extend quizzes with ease—no frameworks, no build tools, just pure web tech.

---

## 🚀 Features

- 🎨 **Modern UI:** Responsive, accessible, and mobile-first  
- 📝 **JSON-Driven:** Add or edit questions in `questions.json`—no code required  
- ⚡ **Instant Feedback:** Real-time answer validation and scoring  
- 🏆 **Persistent High Scores:** Stored in browser localStorage  
- ⏳ **Animated Progress Bar:** Visualizes quiz flow  
- 🌙 **Dark/Light Theme Toggle:** Easily switch between dark and light modes  
- 🔀 **Question & Choice Shuffle:** Randomizes questions and answer order each play  
- 🔊 **Sound Effects & Haptics:** Feedback on correct/wrong answers, with mute option  
- 🛠️ **Developer Friendly:** Modular JS, easy to extend or integrate  
- 🧪 **Testable:** Simple structure for adding unit tests  
- 🔥 **No Dependencies:** 100% vanilla JS, HTML, and CSS  
- 🧹 **Code Quality Tools:** ESLint, Prettier, and Jest for a professional workflow  
- 🚀 **CI/CD Integration:** Automated linting, testing, and deploy via GitHub Actions  

---

## 🗂️ Project Structure

```
Quiz App Master/
├── app.css
├── end.html
├── end.js
├── game.css
├── game.html
├── game.js
├── highscores.css
├── highscores.html
├── highscores.js
├── index.html
├── questions.json
├── theme.js
├── correct.mp3
├── wrong.mp3
├── .eslintrc.json
├── .prettierrc
├── __tests__/
│   └── shuffle.test.js
├── .github/
│   └── workflows/
│       └── ci.yml
└── README.md
```

---

## 🛠️ Getting Started

1. **Clone the repo**
   ```sh
   git clone <repo-url>
   cd "Quiz App Master"
   ```

2. **Install dev dependencies (for linting/testing)**
   ```sh
   npm install
   ```

3. **Open in your browser**
   ```sh
   $BROWSER index.html
   ```
   Or use a local server for best results (e.g., VS Code Live Server).

4. **Start hacking!**
   - Edit `questions.json` to add your own questions.
   - Tweak the UI in `app.css`, `game.css`, etc.
   - Extend logic in `game.js` or add new features.

---

## 🧩 Customizing Questions

Just edit [`questions.json`](Quiz%20App%20Master/questions.json):

```json
{
  "question": "What is the capital of France?",
  "choice1": "Berlin",
  "choice2": "London",
  "choice3": "Paris",
  "choice4": "Madrid",
  "answer": 3
}
```
- Add as many questions as you like.
- `"answer"` is the correct choice number.

---

## 🌗 Dark/Light Theme Toggle

- Click the 🌙 Toggle Theme button to switch between dark and light modes.
- Theme preference is saved in your browser.

---

## 🔀 Question Randomization & Shuffle

- Questions and answer choices are shuffled every time you play for a unique experience.

---

## 🔊 Sound Effects & Haptics

- Correct and wrong answers play different sounds.
- Haptic feedback on supported devices.
- Mute/unmute button included.

---

## 🧹 Code Quality Tools

- **ESLint** and **Prettier** for code linting and formatting.
- **Jest** for unit testing.
- Run:
  ```sh
  npm run lint
  npm run format
  npm test
  ```

---

## 🚀 CI/CD Integration

- Automated linting, testing, and deployment via GitHub Actions.
- See `.github/workflows/ci.yml` for details.

---

## 🏆 High Scores

- High scores are stored in your browser's localStorage.
- View them anytime on the High Scores page.

---

## 🖼️ Screenshots

| Home Page | Quiz In Progress | End Screen | High Scores |
|:---------:|:----------------:|:----------:|:-----------:|
| ![ |<img width="1541" height="755" alt="Screenshot 2025-08-14 005358" src="https://github.com/user-attachments/assets/0a0f3dcb-8ca4-4b61-9c59-1e0c15db45c5" />
 ![Quiz]<img width="1730" height="957" alt="Screenshot 2025-08-14 005418" src="https://github.com/user-attachments/assets/dcfecf21-820d-4ba7-808d-8fe1851aecef" />
 | ![End](https://placehold.co/250x150?text=End) | ![Scores](https://placehold.co/250x150?text=Scores) |

---

## 🤝 Contributing

Pull requests and feature ideas are welcome!  
Open an issue or fork and submit a PR.

---

## 📄 License

MIT License

---

<p align="center">
  <b>Made with ❤️ by Kajal Mishra, for developers.</b> add this 
