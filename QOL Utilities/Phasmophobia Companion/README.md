# 👻 EZ Phasmo Companion

A lightweight, browser-based investigation journal for **Phasmophobia**. Log evidence as you find it and watch the list of possible ghosts narrow in real time — no install, no accounts, no permissions.

> Part of the \*\*Quality of Life for Phasmophobia\*\* project by QOL2026.

\---

## ✨ Features

* **Three-state evidence tracking.** Click an evidence item to cycle it through *Found → Ruled out → Unmarked*. Found evidence keeps only matching ghosts; ruled-out evidence eliminates every ghost that would show it.
* **Live ghost candidates.** All 30 ghost types are shown as cards with a running count of what is still possible. The last ghost standing is marked **Confirmed** with a ✓.
* **Behavioral clues.** Log tells that aren't evidence, such as footprints in salt, the breaker being switched on, or writing without a book, to rule out or pinpoint specific ghosts.
* **Manual exclusion.** Cross off a ghost yourself with one click and restore it just as easily.
* **Ghost details.** Open any card to see its lore, evidence profile, hunt speed, hunt sanity threshold, strength and weakness.
* **Master grid.** A sortable comparison table of every ghost: speed range, hunt %, evidence, strengths, weaknesses and current status.
* **Hide ruled out.** Toggle eliminated ghosts out of view to focus on what's left.
* **Remembers your layout.** View preferences are saved in your browser. Every launch starts a clean case.
* **Spoiler-free.** The companion only works from what *you* log. It never reads the game or reveals the ghost.
* **Private by design.** Runs entirely in your browser. No microphone, screen-sharing or audio access, and nothing is uploaded.

## 📦 What's inside

|File|Purpose|
|-|-|
|`index.html`|Page layout and dialogs|
|`script.js`|Ghost data, evidence logic, rendering|
|`style.css`|Styling and responsive layout|
|`ghost.ico`|Browser tab icon *(optional)*|

No build step, frameworks or dependencies.

## 🚀 Getting started

**Start Here: open it directly**

Download or clone the repo and open `index.html` in a modern browser (Edge, Chrome or Firefox).


🕹️ How to use
---

1. **Start a contract** and keep the companion open on a second monitor or in another window.
2. **Log evidence** in the dock at the bottom of the screen:

   * 1 click: **Found**
   * 2 clicks: **Ruled out**
   * 3 clicks: back to **Unmarked**
3. **Add behavioral clues** from the *Behavioral clues* panel when you spot a tell.
4. **Cross off ghosts** with the **X** on a card if you've ruled them out another way.
5. **Click any card** (or press Enter/Space on it) for full ghost details.
6. **Open the Master grid** to compare speeds and sort by name or speed.
7. **Clear case** to start fresh for the next contract.

## 🧭 Notes on accuracy

Ghost data reflects the game as understood at the time of writing. Phasmophobia receives regular updates that can change evidence, speeds and abilities. If something looks out of date, please open an issue.

Behavioral clues and manual exclusions are only as reliable as your observations. If you're unsure, leave a clue unmarked rather than risk ruling out the right ghost.

## 🤝 Contributing

Issues and pull requests are welcome, especially:

* Ghost data corrections after game updates
* New, reliable behavioral clues
* Accessibility and layout improvements

Please keep the companion dependency-free and spoiler-free.

## ⚠️ Disclaimer

This is an unofficial, fan-made tool. It is not affiliated with, endorsed by, or connected to Kinetic Games. *Phasmophobia* and all related names are trademarks of their respective owners.

