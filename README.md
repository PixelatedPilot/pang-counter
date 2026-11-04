# The Pang Counter 📚⚡

A hilarious live web app tracking how many times your professor cites their own papers during lecture.

![Live Counter Preview](https://img.shields.io/badge/status-active-brightgreen)
![Free Hosting](https://img.shields.io/badge/hosting-100%25%20free-blue)

---

## 🚀 3 Quick Ways to Host This for Free

### Option 1: Netlify Drop (Fastest — 10 seconds, No CLI required)
1. Open [https://app.netlify.com/drop](https://app.netlify.com/drop) in your browser.
2. Drag and drop this folder (`pang-counter`) directly onto the browser window.
3. Done! You get an instant, free public link (like `https://pang-counter.netlify.app`) with free SSL that you can share with your entire class.

---

### Option 2: Surge.sh (1 Command in Terminal)
From this directory, run:
```bash
npx surge .
```
- Enter your email and a password (first time only).
- Press Enter to confirm domain (e.g. `pang-counter.surge.sh`).
- It is live immediately on the web!

---

### Option 3: GitHub Pages (Permanent & Free)
1. Create a new public repository on [GitHub](https://github.com/new) called `pang-counter`.
2. In your terminal, run:
   ```bash
   git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/pang-counter.git
   git branch -M main
   git push -u origin main
   ```
3. Go to **Settings** → **Pages** → under "Branch" select `main` → click **Save**.
4. Your site will be live at `https://<YOUR_GITHUB_USERNAME>.github.io/pang-counter/`!

---

## ✨ Features
- **Starts at 00**: Clean slate for every lecture.
- **Glowing Red 7-Segment LED Display**: Looks identical to physical alarm clocks and sports scoreboards.
- **Interactive Confetti & Sound Effects**: Built with Web Audio API (no external audio files required, zero latency).
- **Classroom Tools**:
  - `Space` / `Enter` / `↑` to count (+1).
  - `↓` / `Backspace` for Undo (-1).
  - `R` to Reset.
  - "Share" button to copy link for classmates.
  - Edit Professor Name (click the header ✎ to change the name anytime).
  - Timestamp Log of citations.
  - Auto-saved in `localStorage`.
