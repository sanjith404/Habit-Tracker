# Momentum Habit & Daily Goal Studio 🎯

A modern, responsive habit-tracking and daily goal dashboard with live system clock synchronization, weekly check-in matrix, and real-time streak analytics. Built with clean vanilla web standards (HTML5, CSS3, JavaScript) and zero external dependencies.

[License: MIT](https://www.google.com/search?q=LICENSE)
[Deploy with GitHub Pages](https://www.google.com/search?q=https%3A%2F%2Fpages.github.com%2F)
[Pure Vanilla](https://www.google.com/search?q=index.html)

---

## ✨ Features

- **⚡ Real-Time Clock & Dynamic Calendar**: Synchronized with the user's system clock (`new Date()`) to automatically set the current week (Monday–Sunday) and detect midnight rollovers without requiring a backend.
- **📅 Weekly Habit Matrix**: 7-day interactive grid with custom frequency targets (e.g. 5 days/wk), category color badges (`Health`, `Focus`, `Fitness`, `Mindfulness`), and live active streak counters (`🔥 Xd`).
- **📝 Daily Goals & Reflection**: Check off prioritized one-off tasks (`High`, `Med`, `Low`) and record daily win reflections for any selected date.
- **📊 Real-Time SVG Streak Analytics**: Responsive SVG chart visualizing daily completion rates against an 80% streak threshold.
- **🔥 14-Day Consistency Heatmap**: Visual intensity strip displaying multi-week momentum at a glance.
- **💾 Local Storage Persistence**: Zero server setup required; all habits and daily logs remain securely stored in the user's browser `localStorage`.
- **🌓 Dark Mode & CSV Export**: One-click theme toggle and weekly data export to standard CSV.

---

## 🚀 1-Minute GitHub Pages Deployment (100% Free)

This repository is ready to deploy directly on [GitHub Pages](https://www.google.com/search?q=https%3A%2F%2Fpages.github.com%2F) with zero configuration:

1. **Fork or create a new public repository** on GitHub (e.g., `habit-tracker`).
2. **Push or upload these repository files** (`index.html`, `style.css`, `app.js`, `README.md`, `LICENSE`, `.nojekyll`) to your `main` branch.
3. In your GitHub repository, open **Settings** → **Pages** (under "Code and automation").
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`
   - **Branch**: Select `main` and `/ (root)`
   - Click **Save**.
5. Your dashboard will be live in 30–60 seconds at:
   ```
   https://<your-username>.github.io/habit-tracker/
   ```

---

## 💻 Running Locally

No package managers (`npm`), runtimes, or build steps required. Clone and open `index.html` in your browser:

```bash
git clone https://github.com/<your-username>/habit-tracker.git
cd habit-tracker

# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

---

## 📁 Repository Structure

```text
habit-tracker/
├── index.html        # Clean semantic markup and UI skeleton
├── style.css         # Modern design system, light/dark themes, and responsive layout
├── app.js            # Real-time state management, SVG charting, and local storage
├── .nojekyll         # Disables Jekyll processing for direct static asset delivery
├── README.md         # Documentation, feature overview, and deployment guide
└── LICENSE           # MIT Open Source License
```

---

## 📄 License

Distributed under the [MIT License](https://www.google.com/search?q=LICENSE).
