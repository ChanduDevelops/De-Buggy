# CodeVision 🚀

A single-file, browser-based code execution visualizer for stepping through code line-by-line, watching memory frames, variables, pointers, and 2D data structures evolve.

## Key Features

* **6 Languages Supported:** Python 3, Java, JavaScript (ES6+), C (C17), C++ (C++20), and C# (.NET).
* **99,999 Execution Steps:** Trace long loops, recursion, and dynamic programming tables without hitting traditional 1,000-step limits.
* **Interactive Memory & 2D Structures:**
* Call stack frames with local variables and lexical parent frames (`[f1]`).
* Top-down 2D hierarchical trees for binary trees.
* Diagonal pointer chains with curved arrows for linked lists.


* **Built-In Debugger:** Gutter click breakpoints, step navigation (`●< BP`, `BP >●`), execution heatmaps, and watch/history tabs.
* **Themes:** AMOLED Black/Monokai Pro dark theme with quick toggles for 🌙 Dark, ☀️ Light, or 💻 Auto.

## Quick Start

1. Open `https://chandudevelops.github.io/De-Buggy/` in any modern browser (Chrome, Edge, Firefox, Brave, Safari).
2. Type your code, pick your language, and click **▶ Visualize** (or press `Ctrl + Enter` / `Cmd + Enter`).

## Keyboard Shortcuts

* **`Ctrl + Enter` / `Cmd + Enter**`: Visualize current code
* **`Right Arrow` / `Left Arrow**`: Step forward / backward
* **`Space`**: Play / Pause auto-stepping
* **`Home` / `End**`: Jump to first / final step