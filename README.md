<div align="center">

#  📃 Hyper-Dense Cheat Sheets

**A curated collection of pixel-perfect, single-page reference sheets for developers, engineers, and sysadmins.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Format: HTML/CSS](https://img.shields.io/badge/Format-HTML%20%2B%20CSS-teal.svg)](#)
[![Status: Active](https://img.shields.io/badge/Status-Active-success.svg)](#)

</div>

---

Welcome to **Cheat Sheets**. This repository is dedicated to completely eliminating the frustration of multi-page, bloated, and unreadable reference guides. 

Every cheat sheet in this repository is engineered with a strict **Zero-Spillover** philosophy: no matter how complex the tool, the guide is aggressively optimized to fit on exactly **ONE physical printed page** (A4 or US Letter) with zero wasted space.

## 🧠 The Design Philosophy

* **Zero Spillover:** Strict `@page` print constraints ensure the content never bleeds onto a second page.
* **Maximum Density:** Utilizing CSS Grid/Flexbox, microscopic (but highly legible) typography, and minimal margins to pack the maximum amount of utility into a single view.
* **High-Contrast Theming:** Custom color palettes (like Slate & Teal) designed for instant visual grepping and reduced cognitive load.
* **No Build Steps:** Raw HTML and CSS. No Markdown converters, no Python scripts, no bloated dependencies. Just open in a browser and print.

---

## 🗂️ Current Roster

### 1. [Tmux Ultimate Cheat Sheet](./tmux/tmux.pdf)
The inaugural sheet of the repo. A comprehensive guide to mastering the ultimate terminal multiplexer. 
* **Covers:** Quick Start, SSH Survival Workflow, Session CLI & Keybindings, Windows (Tabs), Panes (Splits), Navigation, Copy Mode, Resizing, and Mouse Customization.
* **Format:** HTML/CSS (3-Column Grid)
* **Theme:** Modern Slate & Teal

🚧 *(More sheets coming soon...)*

---

## 🖨️ How to Render & Print

Because these sheets rely on precise CSS print media queries, follow these steps to get the perfect PDF or physical copy:

1.  **Open** the desired `.html` file natively in any modern web browser (Chrome, Edge, Firefox, Safari).
2.  **Open the Print Dialog** by pressing `Ctrl + P` (Windows/Linux) or `Cmd + P` (Mac).
3.  **Configure Print Settings:**
    * **Destination:** *Save as PDF* (or select your printer).
    * **Paper Size:** *A4* or *US Letter*.
    * **Layout:** *Portrait*.
    * **Margins:** Set to *Default* or *None* (the HTML file has strict `@page` margins built-in).
    * **Scale:** *100%* or *Default*.
    * **Background Graphics:** **MUST BE ENABLED** (to render the colored headers, keyboard keys, and tip boxes).
4.  **Print/Save!**

---

## 🤝 Contributing

Got an idea for a new tool that desperately needs a hyper-dense reference card? 

1. Fork the repo.
2. Copy the boilerplate HTML/CSS layout.
3. Swap out the commands and colors.
4. Test it in the print dialog to ensure **Zero Spillover**.
5. Submit a PR!

> **Note:** Submissions must adhere to the single-page rule. If your content spills over, you must edit, condense, or drop the least-used commands. Density is the priority.
