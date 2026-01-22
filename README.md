# ⚔️ D&D 5e DPR Simulator

A lightweight, interactive web tool to simulate and visualize Damage Per Round (DPR) for Dungeons & Dragons 5th Edition. 

Built with a focus on transparency, this tool shows you exactly **how** the math is calculated in real-time as you drag dice and toggle modifiers.



![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

* **Split-Screen Dashboard:** View your metrics, graph, and calculation log side-by-side with your build inputs.
* **Drag-and-Drop Dice:** Drag d4, d6, d8, d10, d12, or d20s directly into attack rows.
* **Multi-Round Simulation:** Configure up to 4 unique rounds (e.g., set up a "Nova" round with buffs, followed by standard attacks).
* **Live Math Log:** See the exact formula used for every calculation: `(Hit% × Avg) + (Crit% × Dice)`.
* **Visual Graph:** A line chart powered by Chart.js projects cumulative damage over the combat duration.
* **Pro Modifiers:** Buttons for **Advantage** and **Bless**, plus custom "To Hit" and "Flat Damage" inputs.

## 🚀 Usage

This simulator runs entirely in the browser with no backend required.

1.  **Download:** Clone this repo or download the `dnd-damage-calc.html` file.
2.  **Run:** Open `dnd-damage-calc.html` in any modern web browser (Chrome, Firefox, Edge).
3.  **Simulate:**
    * Set the **Target AC** in the top dashboard.
    * Configure your attacks in the bottom panel.
    * Drag dice from the blue palette into the white dice trays.
    * Watch the math update instantly!

## 🧮 How It Works

The calculator uses standard 5e probability math.

Here is how it looks:

![dmg-calc](https://github.com/user-attachments/assets/dbc67faa-66a0-440d-a2fe-85b47f417886)
