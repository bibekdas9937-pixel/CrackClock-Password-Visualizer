# ⏱ CrackClock — Live Password Crack Time Visualizer

A single-page cybersecurity awareness tool that shows **exactly how long it would take a hacker to crack your password** — in real time, as you type.

🔗 **Live Demo:** Open `index.html` in any browser — no install required.

---

## 🎯 What it does

- Calculates real crack-time estimates using **zxcvbn** (the same entropy-estimation library used by Dropbox)
- Animates a color-coded clock ring that updates live as you type
- Gives specific, actionable feedback — not just "weak" or "strong"
- 100% client-side — nothing you type is stored, logged, or transmitted

---

## 🚀 How to run

No installation needed.

```bash
git clone https://github.com/YOUR-USERNAME/CrackClock-Password-Visualizer.git
cd CrackClock-Password-Visualizer
```

Then just **double-click `index.html`** — it opens directly in your browser.

Or serve it locally:
```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML / CSS / JavaScript |
| Password Analysis | [zxcvbn.js](https://github.com/dropbox/zxcvbn) |
| Hosting | Static — works anywhere (GitHub Pages, local file, any web server) |

---

## 📸 How it works

1. Type any password in the input field
2. The clock ring instantly shows estimated crack time (seconds → centuries)
3. The strength bar and color update live
4. Live tips tell you exactly what's missing (length, symbols, numbers, etc.)

Try the built-in example buttons to compare a weak password vs a strong one side-by-side.

---

## 🎓 Why this project matters

Most password checkers just label a password "weak" or "strong" with no explanation. CrackClock makes the threat **tangible** — watching a clock count down from "centuries" to "instantly" when you remove a single symbol makes the lesson stick in a way a static label never does.

---

## 📄 License

MIT — free to use, modify, and share for educational purposes.

---

Built as a cybersecurity awareness project.
