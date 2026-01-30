# Joke-Generator
# Compliment & Joke Card 🎴✨
A playful, fixed-size “playing card” web app that generates uplifting compliments and family-friendly jokes with a soft pastel aesthetic and smooth micro-interactions — built in **vanilla HTML/CSS/JavaScript** (no frameworks).

---

## Demo
- **Live demo:** *(add your GitHub Pages link here)*
- **Repository:** *(this repository)*

---

## What it does
- ✅ Generates **100 unique compliments** (shuffled “bag” system to reduce repeats)
- ✅ Generates **50 family-friendly jokes**
  - If a joke has a **setup + punchline**, the punchline **reveals after a short delay** with a smooth animation
- ✅ **Fixed-size playing card UI** (no layout shifting when text changes)
- ✅ **Copy** the current result to clipboard
- ✅ **Save favorites** (in-session counter + list logic)
- ✅ Optional personalization inputs:
  - Name
  - “Who is this for?”
  - Tone
  - Focus

---

## Why this project (portfolio value)
This project was built to show strong frontend fundamentals and polished UI execution.

### What this demonstrates
- **UI/UX thinking:** fixed-size card prevents layout jumps, clear hierarchy, friendly microcopy
- **Micro-interactions:** smooth fade transitions, delayed punchline reveal, hover/active states
- **State management:** total counter, saved counter, last output tracking, punchline timer cleanup
- **Data handling:** large preset arrays (100 compliments + 50 jokes), shuffle bag pattern to reduce repeats
- **Accessibility basics:** readable contrast, semantic layout, keyboard support

---

## Keyboard shortcuts
- **Enter** (while focused in an input/select): generate using your last selected mode
- **C**: generate a compliment
- **J**: generate a joke

---

## Tech stack
- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6+)**
- Optional: **Font Awesome** (loaded via CDN)

---

## Project structure
```bash
/
└── index.html   # Everything in one file (styles + script embedded)


Roadmap (optional ideas)

Save favorites permanently using localStorage

Add category filters (jokes: animals/tech/school, etc.)

Add a “Share” button (copy formatted text)

Add sound or subtle haptics (mobile)

License

MIT — feel free to use, remix, and learn from it.